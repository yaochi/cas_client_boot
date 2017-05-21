# cas_client_boot
cas客户端基于spring boot的配置类

参考：

https://github.com/yaochi/cas_client_boot_demo

配置：

application.properties中配置：

```

spring.cas.sign-out-filters=/*
spring.cas.auth-filters=/test
spring.cas.validate-filters=/test
spring.cas.request-wrapper-filters=/*
spring.cas.assertion-filters=/*

spring.cas.cas-server-login-url=https://cas.castest.com:8443/cas/login
spring.cas.cas-server-url-prefix=https://cas.castest.com:8443/cas/
spring.cas.redirect-after-validation=true
spring.cas.use-session=true
spring.cas.server-name=http://www.zrk1000.com:8081
```

新版本：

```


```

