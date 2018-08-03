# Cài đặt 1 project IONIC mới

## Tạo một project

```base
ionic start {appname} {template}
```

* template: tabs, sidemenus...
* Example: tạo ứng dụng my-todo: **ionic start my-todo blank**

### Xem project trên Browser

```base
cd my-todo
ionic serve --lab
```

* --lab: xem dạng mobile
* url test: http://localhost:8100/ionic-lab#

### Test Project trên Emulator Android

```cmd
// Cài build cho ios
$ ionic cordova build ios
$ ionic cordova emulate ios

// Cài build cho Android
$ ionic cordova build android
$ ionic cordova emulate android

// Chạy trên Android
$ ionic cordova run android

// Debug trên máy ảo Android
ionic cordova run android --livereload
```

**Ghi chú:**
* Cài Enviroment Variable:

JAVA_HOME
C:\Program Files\Java\jdk1.8.0_161

ANDROID_HOME
C:\Users\ADMIN\AppData\Local\Android\Sdk

GRADLE_HOME
C:\Users\ADMIN\.gradle\wrapper\dists\gradle-4.1-all\bzyivzo6n839fup2jbap0tjew\gradle-4.1

* Thêm vào Path: 
%JAVA_HOME%\bin
%JAVA_HOME%\bin
%ANDROID_HOME%
%ANDROID_HOME%\tools
%ANDROID_HOME%\platform-tools
%GRADLE_HOME%
%GRADLE_HOME%\bin


***
**Tham khảo:**
https://techmaster.vn/posts/34090/tao-ra-ung-dung-mobile-dau-tien-cua-ban-voi-angularjs-va-ionic