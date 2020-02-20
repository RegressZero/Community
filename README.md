##归零社区  

##资料  
[Spring 文档](https://spring.io/guides)  
[Spring Web文档](https://spring.io/guides/gs/serving-web-content/)  
[Es社区](https://elasticsearch.cn/)  
[Bootstrap](https://v3.bootcss.com/)  
[Github OAuth](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/)  
[OkHttp](https://square.github.io/okhttp/)  
[H2 Database Engine](http://www.h2database.com/html/main.html)  
[Mybatis](http://mybatis.org/spring-boot-starter/mybatis-spring-boot-autoconfigure/)
[Spring Boot Reference Guide](https://docs.spring.io/spring-boot/docs/2.0.0.RC1/reference/htmlsingle/)   
##工具  
[Git](https://git-scm.com/git)  

##脚本
```sql
create table USER
(
	ID INTEGER auto_increment,
	ACCOUNT_ID VARCHAR(100),
	NAME VARCHAR(50),
	TOKEN VARCHAR(36),
	GMT_CREATE BIGINT,
	GMT_MODIFIED BIGINT,
	constraint USER_PK
		primary key (ID)
);
```