# enterprise
## 特性：

通用性企业门户网站

开发语言：Java

模版引擎：JSP

数 据 库：MySQL

核心框架：Spring、SpringMVC、mybatis

## 快速开始

* IDEA导入项目

* 新建数据库enterprise,导入enterprise.sql文件

* 使用tomcat启动

* 前端地址：http://localhost:8080

* 后端地址：http://localhost:8080/manage/user/login



# 下面是我遇到的几个坑
* 使用maven命令运行，命令:mvn tomcat7:run
* 用户名：admin  密码：123456
* 因为我的是docker下的mysql 5.7.9 ，所以我修改了pom.xml文件 mysql-connector-java版本为：5.1.49
* 首页图片显示不正常，是因为修改了端口，请修改对应表：t_systemsetting里面的端口号。
