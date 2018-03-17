# Cài đặt NodeJS và npm trên Window

<!-- TOC -->

- [Cài đặt NodeJS và npm trên Window](#cài-đặt-nodejs-và-npm-trên-window)
    - [Trợ giúp Node](#trợ-giúp-node)
    - [Kiểm tra phiên bản Node](#kiểm-tra-phiên-bản-node)
    - [Chạy 1 file JS nội dung sau: console.log("Xin chào");](#chạy-1-file-js-nội-dung-sau-consolelogxin-chào)
    - [Chạy lệnh node, npm trong CMD:](#chạy-lệnh-node-npm-trong-cmd)
        - [Cài đặt](#cài-đặt)

<!-- /TOC -->

## Trợ giúp Node 

>node --help

## Kiểm tra phiên bản Node

>node --version

## Chạy 1 file JS nội dung sau: console.log("Xin chào");

C:\Program Files\nodejs>node c:\users\nghia\desktop\abc.js
Xin chào

## Chạy lệnh node, npm trong CMD:

### Cài đặt

1. Truy cập vào thư mục cài đặt Node.JS, mặc định:
2. Nếu bạn cài bản x86 thì đó là C:\Program Files (x86)\nodejs\
3. Nếu bạn cài bản x64 thì đó là C:\Program Files\nodejs\
4. Đè phím SHIFT và nhấn chuột phải > **Open command windows here**

```
Gõ vào các lệnh sau:
set path=%PATH%;%CD%  
setx path “%PATH%” 
```

5. Thử vào bất cứ thư mục nào gõ các lệnh sau để kiểm tra:

```
$ node -v
v0.10.35

$ npm -v
1.48.28
```