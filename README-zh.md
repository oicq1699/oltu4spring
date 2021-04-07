# oltu4spring
这个项目想创建一个基于Spring框架的apache oltu库，这个库将去除原有的第三方jar依赖，仅依赖jdk8和spring框架自带的Jar包（主要是springMVC依赖的jar包)。如果能力允许，也会尝试对一些已有bug做一些修复（因为oltu 已经没人维护了）



## 起因

想在项目中搭建 Oauth2   服务，项目是基于Spring的，但是Spring 安全框架已经放弃  authorization server  ，而改为Spring安全框架团队主导的社区版[authorization server](https://github.com/spring-projects-experimental/spring-authorization-server)，这个版本目前感觉并不是太合适。网上搜索了一下，其他项目都有较多的第三方jar依赖（有依赖就会有潜在冲突），比较适合自己的是oltu。但是oltu已经很久无人维护了，并且也依赖了一些三方jar包，我觉得可以尝试使用jdk8和spring 本身(或多数项目依赖的jar包，例如jackson)，从而去除现有依赖的其他jar包。另外，如果能力允许，也会尝试对一些已有bug做一些修复。





