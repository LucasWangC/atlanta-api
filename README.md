这个项目用于自己练习spring cloud

* eureka:服务发现,实现服务注册中心--Netflix Eureka
* config:分布式配置,它包含了Client和Server两个部分。--Spring Cloud Config
* zuul:服务网管--Netflix Zuul
* ribbon:客户端负载均衡--Netflix Ribbon
* sleuth:日志收集工具包，封装了Dapper和log-based追踪以及Zipkin和HTrace操作，为SpringCloud应用实现了一种分布式追踪解决方案。
* Hystrix Dashboard:通过Hystrix Dashboard我们可以在直观地看到各Hystrix Command的请求响应时间, 请求成功率等数据. 但是只使用Hystrix Dashboard的话, 你只能看到单个应用内的服务信息, 这明显不够. 我们需要一个工具能让我们汇总系统内多个服务的数据并显示到Hystrix Dashboard上, 这个工具就是Turbine.