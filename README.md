# swagger2
swagger2组件使用步骤：
* 在目标系统中添加swagger2 jar包依赖
```java
	<dependency>
			<groupId>com.cjkj</groupId>
			<artifactId>cjkj-swagger2-spring-boot-starter</artifactId>
		</dependency>
```
* 在目标系统中添加swagger2 属性值配置
```java
  swagger:
    enabled: true
    title: 用户中心
    description: 用户中心接口文档
    version: 1.0
    host: ${swagger.host}
    basePackage: com.company.admin.modules.sys.controller
```
