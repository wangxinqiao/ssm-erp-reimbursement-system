# ssm ERP报销系统

## 项目介绍
ssm ERP报销系统。主要分4个角色，总经理、部门经理、财务、普通员工，普通员工填写报销单后需要提交给部门经理审核，再由财务支付，如果金额大于5000，还需要总经理审核。

总经理拥有 部门管理 和 员工管理 功能
部门经理拥有 员工管理 功能
其他职务没有

演示视频：[ **点此查看** ](https://www.bilibili.com/video/BV1Pb4y1D7WV/)
源码获取：[ **点此获取** ](http://www.shuyue.fun/?type=productinfo&id=202)

## 环境需要
````
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目
6.数据库：MySql 5.7版本；
````

## 技术栈
1. 后端：Spring SpringMVC MyBatis
2. 前端：JSP+LayUI+jQuery

## 主要技术
- Spring Ioc
- Mybatis+Spring整合
- 声明式事务
- Spring标签库
- Spring拦截器

## 软件架构
三层架构
- 持久层--Mybatis
- 表现层--Spring MVC
- 控制器--Spring Controller

## 基于MVC模式
- 视图--Jsp
- 模型--JavaBean
- 业务层--JavaBean

## 使用说明
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 将项目中spring-dao.xml配置文件中的数据库配置改为自己的配置
3. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
4. 运行项目，输入localhost:8080/xxx 登录

## 账户说明
````
系统默认用户里有四个，分别对应10001（总经理）,10002（部门经理）,10003（财务）,10004（普通员工）
密码为000000
员工填写报销单后需要提交给部门经理审核，再由财务支付，
如果金额大于5000，还需要总经理审核。
总经理拥有 部门管理 和 员工管理 功能
部门经理拥有 员工管理 功能
其他职务没有
````

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/173525_618e5788_9599746.jpeg "报销单流程.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/173538_d0be150d_9599746.jpeg "数据库表ER图.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/173546_ecde0d42_9599746.jpeg "WechatIMG1743.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/173553_a343d782_9599746.jpeg "WechatIMG1744.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/173601_46b6d49e_9599746.jpeg "WechatIMG1745.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/173610_3cb87734_9599746.jpeg "WechatIMG1746.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/173617_4b28063f_9599746.jpeg "WechatIMG1747.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/173627_b9fb28df_9599746.jpeg "WechatIMG1748.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/173635_5757c12b_9599746.jpeg "WechatIMG1749.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/173644_399884cc_9599746.jpeg "WechatIMG1750.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/173652_4f78c2ad_9599746.jpeg "WechatIMG1751.jpeg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0817/173659_9192928f_9599746.jpeg "WX20210405-162019@2x.jpeg")







