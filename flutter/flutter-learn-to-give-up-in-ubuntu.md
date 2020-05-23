Ubuntu上使用Flutter踩坑放弃史
---

## 为什么是Ubuntu上面使用？

因为公司的电脑是Windows的，但因为各种加密使用flutter容易报错（最近使用报我的坑！），想想就算了，自身对Flutter技术也一直持观望态度

近来将自已的Linux系统使用起来了，然后。。。坑史


## 哪些坑

### WINDOWS被加密软件搞废

只能用正常的Java和Kotlin，Flutter不好意思，被废，不想找网络修改权限

### 网络的坑

从2.4G（带我的多年的前的WIFI网卡插在电脑上使用） -> 网线解决

### 网络代理的坑

使用了Clash代理，也是各种坑！！

### 还是代理的坑，是`flutter`指令请求相关的

这个功能是压倒我在Ubuntu上使用`flutter`的最后一根稻草

## 总结

千丝万语就是不打算在Ubuntu上面使用，总结是《`flutter` && `proxy` && `gradle` && `pub get`》合力的坑，单独解其中几个没有问题，合起来就废了，用了好不爽。。。。耽搁耽搁

Ubuntu20.04 Flutter， GoodBye！
