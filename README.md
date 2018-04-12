


# 联系方式

- 手机：13075534552
- Email：zz51zhen@gmail.com
- QQ：527844046
- 微信：zz527844046

---

# 个人信息

 - 张震/男/1995
 - 专科/新华学院计算机系 
 - 工作年限：3年
 - 技术博客：http://www.cnblogs.com/zzdylan
 - Github：https://github.com/zzDylan

 - 期望职位：PHP程序员
 - 期望薪资：税前月薪15k~20k
 - 期望城市：北京

---

# 工作经历

## 上海璇嘉信息技术有限公司 （ 2017年7月 ~ 至今 ）

### 以诺教育
项目背景：《以诺教育》是一个面向高净值人群的游学项目在线展示与报名应用。  
我负责了这个项目的服务器环境搭建（nginx、php、mysql）、后台管理系统以及pc端和小程序端的api接口、定时任务和队列等。
该项目后端使用laravel5.4。  
后台管理系统：  
框架搭建、权限系统、优惠券、订单管理、课程管理、广告管理等
api接口：  
小程序支付、支付宝支付、退款接口等


### 无人值守超市
项目背景：  
搭建服务器环境、微信页面制作、后台管理系统以及后端接口开发，微信授权以及微信支付。
该项目后端使用laravel5.4。
硬件包括无人值守超市的人扫描器、自动门以及rfid扫描器等接口的对接。

 
## 上海徽保网络科技有限公司 （ 2016年11月 ~ 2017年7月 ）

### 众利保
担任项目的主要后端工程师，负责该项目的后端接口开发、微信开发和后台管理系统开发，搭建服务器环境和git环境，维护服务器。
该项目后端使用thinkphp3.2。
众利保是一个保险第三方平台，跟各大保险公司对接之后，让用户可以在一个平台购买多个平台的实惠产品。

## 耐特加 （ 2015年10月 ~ 2016年11月 ）

### 校园网上食堂
担任项目的主要后端工程师
该项目后端使用laravel5.2。
微信授权、微信支付、阿里云存储、优惠券、公告、任务调度





---

# 个人作品

## laravel5.5+workman+vue开发的聊天室项目：

这个一个有趣的聊天室项目，使用workman来实现websocket，使用laravel做mvc后端，vue2做前端，用户可以注册、登陆、群聊等。
用户注册成功后，会进入聊天室，这个时候会通过websocket请求服务端，服务器会分配一个唯一的client_id给客户端，这个时候需要将用户的uid和client_id绑定上，uid和client_id是一对多的关系，client_id的生命周期等于客户端和服务器的连接周期，当断开连接时，client_id便会失效。绑定成功以后、用户可以在聊天室中发文字或者图片，文字和图片的发送均通过ajax请求，响应成功后会通过workman的gatewayclient给客户端推送消息，以便让其他用户收到该用户发送的消息。本项目还对接了图灵机器人，当聊天室没啥人的时候，可以让图灵机器人陪别人解解闷。图灵机器人的消息使用队列发送。
用到的组件有：
qiniu-laravel-storage:七牛云存储的sdk
jwt：使用json web token的方式授权
intervention/image:对图片进行压缩处理
gateway-worker：实现websocket
gatewayclient：实现mvc和websocket的结合
项目体验地址:[http://dev10.shareg.cn][1]

## 基础后台管理系统模板：

开发过多个后台管理系统之后，疲惫重复性的一些开发，于是便自己写了一个通用的基础后台管理系统，后端使用laravel5.4，前端使用adminlte，实现的功能有后台用户管理、角色管理、权限管理、菜单管理等，已经在多个项目中运用。现在准备继续写一个以composer扩展形式的laravel包，通过安composer装添加后台管理系统到现有的项目中。


# 技能清单

以下均为我熟练使用的技能

- Web开发：PHP、javascript、html
- Web框架：ThinkPHP/Laravel
- php相关扩展或类库：easywechat、workman、swoole、Laravel-Excel、Intervention/image、jwt-auth、dingoapi等
- linux：nginx、php、mysql环境搭建以及配置，负载均衡以及服务器日常维护。了解应用容器技术，使用 docker 搭建运行 lnmp 站点。
  熟悉 linux 操作，掌握 linux 常用命令和服务、如 LA/NMP 环境搭建，
  shell 脚本的编写、Vi/Vim 操作、定时任务 crontab 的编写、ab 测试
  工具的使用。Python 能够熟练搭建运行环境，编写简单的系统脚本
- 前端框架：jQuery/Bootstrap/AngularJS/ionic/vuejs
- 前端常用库：echarts、layer、jquery-form、bootstrap-fileinput、bootstrap-validator
- 前端工具：Bower/Gulp/PhoneGap/webpack
- 前端性能优化：可以从多个方面去分析需要性能优化点，如 CDN、
  HTTP 请求、JS/CSS 加载、DNS 解析等
- 数据库相关：MySQL/PDO/redis
- 版本管理、文档和自动化部署工具：Svn/Git/swagger/Composer
- 云和开放平台：SAE/BAE/AWS/阿里云/腾讯云/微博开放平台/微信应用开发

## 自我评价

### 给自己的定位：
主攻后端，同时在其他方面打打辅助，力求做到在任何需要我的时候都能顶上去解决问题，关注 PHP 的动态和其他最新的科技资讯。
### 对工作的态度：
第一，高效完成本职工作，第二，在完成的基础上寻找完美，第三，在完美的基础上与其他同事交流，相互学习，相互提升。工作是一种生活方式，不是一份养家糊口的差事
### 喜欢的社区
开源中国，segmentfault，Stack Overflow，博客园，csdn，简书、laravel-china、laravel学院等

---

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。


  [1]: http://dev10.shareg.cn