# tls_sigature

## 介绍
Android端生成腾讯视频云userSig和privateMapKey的算法

*(从腾讯视频云官网业务生成算法移植)*

## 使用示例

```Java
tls_sigature tls = new tls_sigature().setSdkAppid(sdkAppId)
                .setPrivateKey(privateKey);
String userSig = tls.genUserSig(userId, 3600*1000);
```
