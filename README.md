https://blog.csdn.net/sunroyi666/article/details/95189938

# SpringCloud

SpringBoot微服务相关架构

（1）搭建SpringBootService，这里是各个微服务的业务逻辑。（这里搭建了2个Service，用来测试熔断）

（2）搭建SpringBootEureka，用来发现服务。

（3）搭建SpringBootConfig，用于动态维护配置文件。

（4）搭建SpringBootConsumer，这个不是必须的，只有当一个更大的业务需要调用其他多个微服务Service时才需要搭建。

（5）搭建SpringBootZuul，用于路由控制。可以加入Hystrix用于熔断处理。

（6）使用Jenkins进行代码的自动化部署。
