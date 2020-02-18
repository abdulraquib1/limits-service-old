
# Spring Cloud : Config Server
 
** Demonstrates Configuration server setup and linking with the Service properties **


* Default Properties [http://localhost:8888/limits-service/default](http://localhost:8888/limits-service/default)
* Dev Properties [http://localhost:8888/limits-service/dev](http://localhost:8888/limits-service/dev)
* QA Properties [http://localhost:8888/limits-service/qa](http://localhost:8888/limits-service/qa)

** Configuration **

```
spring.cloud.config.server.git.uri=D:\\projects2020\\git-localconfig-repo

```

** Annotations **

```
@EnableConfigServer	
@SpringBootApplication
public class SpringCloudConfigServerApplication { }

```



** References **

[Spring properties reference](https://docs.spring.io/spring-boot/docs/current/reference/html/common-application-properties.html)

[MD File Syntax](https://confluence.atlassian.com/bitbucketserver/markdown-syntax-guide-776639995.html)

[In28mins Github Resource Config](https://github.com/in28minutes/spring-microservices/tree/master/03.microservices)
[Install Github on local](https://git-scm.com/)

