如何创建一个 MERN 集合 MongoDb , Express JS , React JS , Node JS 全栈教程

你知道如何创建 MERN 全栈吗？你知道什么是 MERN 全栈？你知道什么情况下需要一个 MERN   全栈吗？

这篇文章，我将会教你创建一个简单的 MERN 全栈应用

首先，MERN 全栈是由 MongoDB ExpressJS Reactjs NodeJS 四个教程组成；

MongoDB：一个可扩展、灵活的文档型数据库；
ExpressJS ：一个用于设计 Web 应用开发服务框架；
ReactJS：一个由 Facebook 维护，用于构建用户界面的 Javascript 前端框架；
NodeJS：一个基于 Chrome V8 引擎的 JavaScript 运行环境；

我相信任何最好的学习路径就是通过实践，下面的将会创建一套简单的 CRUD 实践；

1.创建后端应用

我们通过 RESTful 的步骤来创建后端服务；

第一步，创建一个空文件夹作为系统根目录；

$ mkdir movies-app
$ cd movies-app

之后创建一个 server 的空文件夹，作为我们的后端文件夹；

我们接下来我们会创建 package.json 的文件；

package.json 文件只是 Nodejs 项目的一个清单，包含了项目的数据，在 package.json  
当中你可以管理项目的依赖，在 script 中设置可以安装依赖环境、构建生产环境、跑测试等一系列事情；

创建 package.json 需要包管理工具，可以选用 NPM 或者 YARN ，按照使用习惯选择就行；

在根目录下运行指令创建 package.json

$ yarn initor

$ npm init -y
