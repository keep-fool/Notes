# Nginx

* [学习视频地址](https://time.geekbang.org/course/detail/138-65063)

## 场景

1. 静态资源服务
2. 反向代理服务
3. API服务

## 优点

* 高并发 可扩展性 高可靠(年宕机时间以秒计)  
* 热部署(不重启,升级Nginx)  
* BSD许可证(开源 可修改源码 合法)

## 组成  

1. Nginx 二进制可执行模块
2. Nginx.conf 配置文件
3. access.log 访问日志(http请求信息，响应信息)
4. error.log 错误日志

## 更新

* feature 新增功能
* bugfix 修复的BUG
* change 重构内容

## OpenResty

## 编译Nginx

## Nginx目录

* 目录auto 子目录 cc lib os(操作系统) types
* 文件changes changes.ru
* 目录conf示例文件
* 脚本configure 用来生成中间文件
* 目录contrib Nginx专用vim配置文件
* 目录html 500.html index.html
* 目录main linux对Nginx的
