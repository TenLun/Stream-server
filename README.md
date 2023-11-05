# Stream-server
在windows上开启本地rtmp服务器

## __简单来说，就是懒人福利__

打开 ```nginx.exe``` 即可使用

这个仓库提供了打包好的nginx，并带有以下模块
- nginx-http-flv-moudule
- pcre -8.34
- zlib -1.2.11
- openssl -1.0.1u

---

默认 引流/拉流 地址
- rtmp：rtmp://localhost/live/123
- http：http://localhost:8888/live?app=live&stream=123

播放地址 http://localhost:8888

---

地址可以在 ```conf/nginx.conf``` 修改
