# springboot-jwt-demo

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/lwshen/springboot-jwt-demo)

## 简介
这是一个使用了springboot+springSecurity+jwt实现的基于token的权限管理的一个demo

具体说明可以看 **[这里](https://github.com/echisan/springboot-jwt-demo/blob/master/blog_content.md)**

## 使用
更改一下`application.properites`的数据库的一些配置信息，然后就可以运行了

首先注册的url是`/auth/register`
参数很简单就`username`,`password`

然后登陆是`/auth/login`

参数名称 | 类型 | 说明
------- | ---- | ----
username | String | 用户名
password | String | 密码
rememberMe | Interge | 记住我，只有两个值可以选，0:不记住，1:记住

推荐使用postman去测试，登陆成功后在响应头里可以找到token

之后就可以访问`/tasks`了

## 鸣谢

> IntelliJ IDEA 是一个在各个方面都最大程度地提高开发人员的生产力的 IDE, 适用于 JVM 平台语言。

特别感谢 [JetBrains](https://www.jetbrains.com/?from=springboot-jwt-demo) 为开源项目提供免费的 [IntelliJ IDEA](https://www.jetbrains.com/idea/?from=springboot-jwt-demo) 等 IDE 的授权  
[<img src=".github/jetbrains-variant-3.png" width="200"/>](https://www.jetbrains.com/?from=springboot-jwt-demo)
