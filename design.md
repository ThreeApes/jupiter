# Jupiter 简单设计

## 概述

开发一个简单的博客系统玩玩，主要的功能就是发表博客，展示博客，以及游客针对博文评论以及评分。

### 发表博客

开发人员通过页面进行添加。

### 展示博客

对博客进行展示

### 评论评分

进行评分操作的时候需要游客输入用户名即可进行操作。无需繁琐的登录注册操作。

## 一些工具

### 后台

+ Web框架 : [Spring Boot](http://projects.spring.io/spring-boot/)

### 数据库

+ 数据库 : H2(develop), MySQL & MariaDB(deploy)
+ 数据持久化工具 : [Mybatis](http://www.mybatis.org/) 
+ 数据库版本管理工具 : [Flyway](https://flywaydb.org/)

### web 服务器

+ Tomcat
+ Jetty : for test
+ ngnix

### web前端

+ ???

### 服务器

+ CentOS 7


## 数据库表

### Blog 表

+ ID
+ Title
+ Content
+ Excerpt
+ Author
+ CreatedAt
+ UpdatedAt
+ AveragePoint
+ CommentCount
+ Tag ?
+ Type?

### Comment 表

+ ID
+ Creator
+ ToWhom
+ Content





### TODO

讨论完善



