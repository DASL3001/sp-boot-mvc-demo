# sp-boot-mvc-demo

[https://github.com/in28minutes/spring-boot-master-class/edit/master/02.Spring-Boot-Web-Application/Step04.md](https://github.com/in28minutes/spring-boot-master-class/edit/master/02.Spring-Boot-Web-Application/Step04.md)
 
Second Snippet - /src/main/resources/application.properties
```
spring.mvc.view.prefix: /WEB-INF/jsp/
spring.mvc.view.suffix: .jsp
logging.level.: DEBUG
```

Third Snippet : To enable jsp support in embedded tomcat server!
```
        <dependency>
            <groupId>org.apache.tomcat.embed</groupId>
            <artifactId>tomcat-embed-jasper</artifactId>
            <scope>provided</scope>
        </dependency>

```
