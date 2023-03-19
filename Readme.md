
### 功能介绍

平台采用B/S结构，后端采用主流的Python语言进行开发，前端采用主流的Vue.js进行开发。

整个平台包括前台和后台两个部分。

- 前台功能包括：首页、商品详情页、用户中心模块。
- 后台功能包括：总览、订单管理、图书管理、分类管理、标签管理、评论管理、用户管理、运营管理、日志管理、系统信息模块。

### 源码下载

https://github.com/geeeeeeeek/shop

### 演示地址

前台地址： http://1.117.171.66:8003/#/index

后台地址：http://1.117.171.66:8003/#/admin

后台管理帐号：

用户名：admin123
密码：admin123

### 代码结构

- server目录是后端代码
- web目录是前端代码

### 部署运行

#### 后端运行步骤

(1) 安装python 3.8

(2) 安装依赖。进入server目录下，执行 pip install -r requirements.txt

(3) 安装mysql 5.7数据库，并创建数据库，命名为book，创建SQL如下：
```
CREATE DATABASE IF NOT EXISTS shop DEFAULT CHARSET utf8 COLLATE utf8_general_ci
```
(4) 迁移数据。在server目录下依次执行如下命令：

```
python manage.py makemigrations
python manage.py migrate
python manage.py makemigrations myapp
python manage.py migrate myapp
```

(5) 启动django服务。在server目录下执行：
```
python manage.py runserver
```

#### 前端运行步骤

(1) 安装node 16.14

(2) 进入web目录下，安装依赖，执行:
```
npm install 
```
(3) 运行项目
```
npm run serve
```


### 界面预览

首页


后台首页


后台借阅管理



### 待完善功能

- 邮箱推送功能
- 手机号绑定功能
- 粉丝关注功能
- 支付功能

### 问题咨询

微信：lengqin1024


### 打赏作者

