# Mall

mall项目的实现和完成此项目为协作项目

## 前端使用Mall的前端

# 前端

## 前端地址

[macrozheng/mall-admin-web: mall-admin-web是一个电商后台管理系统的前端项目，基于Vue+Element实现。 主要包括商品管理、订单管理、会员管理、促销管理、运营管理、内容管理、统计报表、财务管理、权限管理、设置等功能。 (github.com)](https://github.com/macrozheng/mall-admin-web)

## 前端的部署与安装

[mall前端项目的安装与部署 | mall学习教程 (macrozheng.com)](https://www.macrozheng.com/mall/deploy/mall_deploy_web.html#windows下的安装及部署)

## 可能出现的问题

1.python的版本设置不对，解决方法

~~~bash
1.安装python27在/File下
2.设置
npm config set python C:\Python27
~~~

2.node-sass版本问题

~~~bash
npm install node-sass@latest --sass-binary-site=https://npm.taobao.org/mirrors/node-sass
npm install node-sass@7.0.1
~~~

3.是在不行采用cnpm

~~~bash
npm install -g cnpm --registry=https://registry.npm.taobao.org
cnpm install
~~~

4.解决npm ERR! code ELIFECYCLE npm ERR! errno 1问题

~~~bash
删掉项目中的node_modules文件夹和package-lock.json文件，网上有很多快速删掉node_modules的指令和方法，但是我照搬了一下，发现都不行，所以还是手动删掉是最快的。
~~~

# 后端

## 1.mall整合SpringBoot+MyBatis搭建基本骨架

sql文件放在/File

SpringBoot依赖

[mall整合SpringBoot+MyBatis搭建基本骨架 | mall学习教程 (macrozheng.com)](https://www.macrozheng.com/mall/architect/mall_arch_01.html#添加mybatis的java配置)

主要操作的表为pms_brand

可以先完成mall整合Swagger-UI实现在线API文档

## 2.mall整合Swagger-UI实现在线API文档

[mall整合Swagger-UI实现在线API文档 | mall学习教程 (macrozheng.com)](https://www.macrozheng.com/mall/architect/mall_arch_02.html#项目使用框架介绍)

# 提交

1.项目的提交，因为前端所需依赖较多，前端项目的依赖存放本地，` /Code/mall-admin-web` 只存放前端文件不存放依赖，根据情况修改前端文件

2.提交新建分支，写上备注

# TODO

- [ ] 架构
  - [ ] springboot
  - [ ] my-plus
  - [ ] redis
  - [ ] el（搜索）
- [ ] 业务
  - [ ] 基本业务
- [ ] 部署
  - [ ] linux
  - [ ] docker