# swagger-starter-demo

spring-boot-starter-swagger使用样例

## Swagger 前台访问地址

前台地址，根据使用的spring-boot-starter-swagger版本，不同地址如下：

- 1.x版本：http://{ip}:{port}/{server.servlet.context-path}/swagger-ui.html
- 2.x版本：http://{ip}:{port}/{server.servlet.context-path}/swagger-ui/index.html

当前 Demo 前台地址：http://localhost:8080/swagger-ui/index.html

## 安装

添加依赖

pom.xml

```xml
<dependency>
	<groupId>com.spring4all</groupId>
	<artifactId>swagger-spring-boot-starter</artifactId>
	<version>2.0.0-RELEASE</version>
</dependency>
```

下 XXXApplication.java 启动文件中添加外部扫描包 com.spring4all.swagger

```java
@SpringBootApplication
public class DemoApplication {
    public static void main(String[] args) {
        SpringApplication.run(DemoApplication.class, args);
    }
}
```
