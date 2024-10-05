## 本项目完整源码是收费的  接毕业设计和论文

### 作者QQ：3642795578 微信：grapro666 (支持修改、 部署调试、 支持代做毕设)

### 接网站建设、小程序、H5、APP、各种系统等

**博客地址：
[https://blog.csdn.net/2303_76227485/article/details/138707648](https://blog.csdn.net/2303_76227485/article/details/138707648)**

**视频演示：
[https://www.bilibili.com/video/BV15t421u7U5/](https://www.bilibili.com/video/BV15t421u7U5/)**

**毕业设计所有选题地址：
[https://github.com/zhengjianzhong0107/allProject](https://github.com/zhengjianzhong0107/allProject)**

## 基于Java+Springboot+Vue的医院预约挂号小程序(源代码+数据库)138

## 一、系统介绍
本系统前后端分离带小程序和后台

小程序（用户端），后台管理系统（管理员，医生）

### 1、用户：
- 注册、登录、医院浏览、预约挂号、就诊记录、挂号记录、我的家人、候诊队列、个人信息、忘记密码
### 2、医生：
- 修改密码、出诊详情、用户就诊管理
### 3、管理员：
- 医院管理、科室管理、门诊管理、医生管理、排班管理、统计

## 二、所用技术

后端技术栈：

- Springboot
- Mybatis
- Mysql
- Maven
- Jwt
- SpringSecurity
- redis

前端技术栈：

- Vue 
- Vue-router 
- axios 
- elementui
- 微信小程序

## 三、环境介绍

基础环境:IDEA/eclipse, JDK1.8, Mysql5.7或以上, Maven3.6, node14, navicat, 微信开发者工具, 微信小程序账号, redis5.0

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
### 1、用户
![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
![contents](./picture/picture14.png)
![contents](./picture/picture15.png)
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)
![contents](./picture/picture23.png)

### 2、工作人员：
![contents](./picture/picture24.png)
![contents](./picture/picture25.png)
![contents](./picture/picture26.png)

### 3、管理员：
![contents](./picture/picture27.png)
![contents](./picture/picture28.png)
![contents](./picture/picture29.png)
![contents](./picture/picture30.png)
![contents](./picture/picture31.png)
![contents](./picture/picture32.png)
![contents](./picture/picture33.png)
![contents](./picture/picture34.png)
![contents](./picture/picture35.png)
![contents](./picture/picture36.png)
![contents](./picture/picture37.png)
## 五、浏览地址
- 用户账号/密码：18812341234/123456、15766668888/123456

后台登录页面: http://localhost:8081

- 医生账号/密码：10008/123456、10009/123456
- 管理员账号/密码：admin/admin

## 六、部署教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql

2. 使用IDEA/Eclipse导入hospital-master项目，导入时，若为maven项目请选择maven; 等待依赖下载完成

3. 修改resources目录下面application.yml里面的数据库配置和微信小程序账号秘钥配置

4. cn/yujian95/hospital/HospitalApplication.java启动后端

5. vscode或idea打开vue项目

6. 在编译器中打开terminal，执行npm install 依赖下载完成后执行 npm run dev,执行成功后会显示后台管理访问地址

7. 微信小程序打开hospital-wxapp-master项目，编译好之后就运行成功了

