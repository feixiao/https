## 局域网https支持

#### 环境
+ Ubuntu 18.04 LTS
+ OpenSSL 1.1.1  11 Sep 2018

#### 自签证书
+ [mkcert](https://github.com/FiloSottile/mkcert) 自签证书工具

##### OSX
```
brew install mkcert
mkcert -key-file key.pem -cert-file cert.pem  *.mmc.com
mkcert -install
```

注：windows系统上面根证书(类似： *.xxx.com)无效、osx上面没有问题。

#### 如何使用证书
+ [《实现局域网https域名访问内网服务》](https://juejin.im/post/5ce50576f265da1bb7763fa4)
+ [《golang中使用HTTPS以及TSL》](https://blog.csdn.net/wangshubo1989/article/details/77508738)
