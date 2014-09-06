# 使用 Node.js、Redis 和 Socket.io 创建 HTML5 聊天应用程序

这里是在线聊天工具教程的工程代码

点击查看教程 : [*使用 Node.js、Redis 和 Socket.io 在 Bluemix 上创建 HTML5 聊天应用程序*](https://www.ibm.com/developerworks/cn/web/wa-bluemix-html5chat/)

工程效果演示 : [*Chatroom*](http://chat.nnii.me/).

Code for interesting of chat online software.

Proudly practiced by [Channely](http://Channely.github.io/).

### Method 1: Use local redis db to build node app local

> 0,$ git clone https://github.com/Channely/node-socket-redis-chatroom.git

> 1.$ git checkout localredis

> 2,$ npm install 

> 3,$ sudo apt-get install redis-server  #安装数据库redis 

> 4,$ redis-server  #然后启动数据库 

> 5,$ npm start  #然后启动node服务程序 

> 6,打开localhost:3000 查看效果

### Method 2: Use cloud redis db to build node app remote

> 0,$ git clone https://github.com/Channely/node-socket-redis-chatroom.git

> 1,$ npm install 

> 2,signup for redislabs.com && create a free redis instance && rewrite server.js line:71 the value of host,port,password by your own content in og this new instance

> 3,$ npm start  #然后启动node服务程序 

> 4,打开localhost:3000 查看效果
