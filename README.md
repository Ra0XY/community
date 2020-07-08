## 码匠社区 Spring boot项目
## 资料
[Spring 文档](https://spring.io/guides)  
[Spring Web](https://spring.io/guides/gs/serving-web-content/)  
[es社区](https://elasticsearch.cn/)  
[BootStrap](https://v3.bootcss.com/getting-started/)  
[Gitbub OAuth](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/)  
[Spring](https://docs.spring.io/spring-boot/docs/2.0.0.RC1/reference/htmlsingle/#boot-features-embedded-database-support)

## 工具
[Git](https://git-scm.com/downloads)   
[Visual-Paradigm](https://www.visual-paradigm.com/cn/)

## 脚本
```sql
create table USER
(
    ID int auto_increment primary key not null,
    ACCOUNT_ID   VARCHAR(100),
    NAME         VARCHAR(50),
    TOKEN        CHAR(36),
    GMT_CREATE   BIGINT,
    GMT_MODIFIED BIGINT
);
```