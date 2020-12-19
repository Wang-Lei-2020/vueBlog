# vueBlog
web前端开发 SPA博客

一．	项目概况
本项目是一个基于Vue和Express框架的单页面博客，后端服务器选择的是nodeJS，应用Ajax来实现请求和响应博客，数据库选择的是MongoDB。

二．	项目配置与启动
1.	下载并启动MongoDB数据库，在cmd中进入到/MongoDB/bin位置，输入命令mongod来启动MongoDB数据库（默认端口27017）。
2.	如要想查看MongoDB数据库中的内容，需要另外开启一个cmd窗口，进入到/MongoDB/bin位置，输入命令mongo localhost：27017进行查看数据库的操作。
3.	下载nodeJS服务器，cmd中进入项目所在位置，输入命令node app来打开后端服务器，后端监听 3000 端口。
4.	最后在WebStorm中打开项目，并进行npm配置，最后用npm运行项目。
5.	在浏览器中输入http://localhost:8080/ 即可访问。
