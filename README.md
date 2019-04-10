# NodejsServer
This is a suggested server built by nodejs for client developers to learn the websocket protocol.

client端用Nodejs搭建server

#用Nodejs来搭建一个简易的server服务器#

一、环境搭建

1、安装node环境：brew install node （npm是node自带的功能，如果之前没有安装npm，这个时候会安装上去）
2、查看是否已安装：node -v

上面已经安装好node。


二、配置nodejs

1、首先要设置一个工作文件夹
mkdir websocket

2、在这个工作文件夹下，对其初始化init
npm init

3、接着，添加各种依赖dependency（依赖会被安装在node_module包里）
#我们需要安装一个websocket模块依赖#
npm search ws
npm install ws

语法如下：
npm install <module>   //安装
npm uninstall <module>   //卸载
npm search <module>   //搜索
npm update <module>   //更新

说明：
这种安装是本地安装，安装在命令行所在的文件夹里。
nodejs使用这些依赖时，要用var xx = requires('xxx')去使用。


三、创建Nodejs应用

#Nodejs应用程序的组成
1、引入所需模块var xxx = require(‘xxx’)
2、服务器创建：服务器可以监听客户端的请求
3、接收请求与响应请求：服务器很容易创建，客户端可以使用浏览器或终端发送HTTP请求，服务器接收请求后返回响应数据。


四、启动Nodejs服务
node /Users/wuguanlong/websocket/c3/server.js
注意：
这里node后面应该输入该文件的具体路径
(最简单的方法就是用鼠标将该文件拖拽到终端中，即可获得server.js的总路径)








