# Cài đặt 1 project IONIC mới

## Tạo một project

```base
ionic start {appname} {template}
```

* template: tabs, sidemenus...
* Example: tạo ứng dụng my-todo: **ionic start my-todo blank**

### Chỉ định nền tảng cho project

không dùng cũng được, sẽ build sau.

```base
cd scotch-todo
ionic platform add ios
ionic platform add android
```

### Xem project trên Browser

```base
ionic serve --lab
```

* --lab: xem dạng mobile
* url test: http://localhost:8100/ionic-lab#

***
**Tham khảo:**
https://techmaster.vn/posts/34090/tao-ra-ung-dung-mobile-dau-tien-cua-ban-voi-angularjs-va-ionic