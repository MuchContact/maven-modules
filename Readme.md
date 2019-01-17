# 项目介绍
```
    <parent>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-parent</artifactId>
        <version>2.0.5.RELEASE</version>
    </parent>
```

```
        <profile>
            <id>mysql</id>
            <activation>
                <activeByDefault>true</activeByDefault>
            </activation>
            <properties>
                <database.type>mysql</database.type>
            </properties>
        </profile>
```

> 动态属性和spring-boot-starter-parent的冲突