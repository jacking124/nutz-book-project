# nutz-book-project

nutz-book 衍生出的project

Nutz主库地址 https://github.com/nutzam/nutz 觉得不错, 来个star呗

[![Build Status](https://travis-ci.org/wendal/nutz-book-project.png?branch=master)](https://travis-ci.org/wendal/nutz-book-project)
[![](https://imagelayers.io/badge/wendal/nutzbook:latest.svg)](https://imagelayers.io/?images=wendal/nutzbook:latest 'Get your own badge on imagelayers.io')[![license](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)]()

## 主项目地址

https://github.com/wendal/nutz-book

http://nutzbook.wendal.net

非常欢迎大家自行部署, 请查阅[部署指南](INSTALL.md)


## 在线演示地址

论坛系统(即Nutz社区的官网) https://nutz.cn

* 管理后台  https://nutz.cn/home
* 管理后台2  https://nutz.cn/admin
* 管理后台3 https://nutz.cn/admin2

## 截图

![首页截图](index_page.jpg)


## 主要功能

* 基本的增删改查,MVC各种用法及文件上传
* Dao关联关系(One/Many/ManyMany)
* 邮件发送及基于3DES的无数据库验证机制
* Quartz计划任务集成
* Shiro集成及权限管理
* Ehcache及DaoCache集成
* redis 集成
* beetl模板集成及应用
* 二维码生成及跨屏登陆
* 声明式系统日志
* 基于socialauth的Oauth登陆(客户端,非服务器端实现)
* 集成极光推送(jpush)及小米推送(xmpush)
* WebSocket的简单使用(页面回帖通知)

## 曾经集成,但已经移除的功能

* U2F绑定与登陆
* zbus集成(RPC及MQ)
* jetbrick模板集成
* socketio 集成及demo聊天工具
* 洋葱登录

## 关于目录结构变化

nutzbook中的代码是eclipse结构的, 本项目最新的代码已经改为maven格式, 映射关系如下

* src -- src/main/java
* conf -- src/main/resources
* WebContent -- src/main/webapp

eclipse依然可以直接导入本项目

## 依赖的jar包下载

http://nutzbook.wendal.net/jars/

## License

MIT License或Apache License 双授权协议. -- 事实上我懒得选.

极为宽松,请大胆商用,大胆闭源,本库的代码完全免费. 任选MIT/Apache协议执行即可.