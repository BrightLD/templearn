### 开发工具

------

名称：`vscode`

下载地址：<https://code.visualstudio.com/> 

推荐插件：

   +  Auto Close Tag ：自动修改匹配的 HTML 标签。
   +  View In Browser ：在浏览器里预览网页必备。
   +  vscode-icons：改变编辑器里面的文件图标
   +  Highlight Matching Tag：高亮对应的 HTML 标签 以及 标识出对应的各种括号。
   +  Path Intellisense：智能路径提示，可以在你输入文件路径时智能提示。
   +  Prettier：格式化插件。
   +  GitLens：Git 重度使用者必备，尤其是多人协作时：哪一行代码，何时、何人提交都有记录。
   +  Git History：用来查看git log或则一个文件的git历史，比较不同的分支，commits。
   +  css-auto-prefix：自动添加 CSS 私有前缀。
   +  npm Intellisense：VSCode 插件可以在导入语句自动补全npm模块名称。
   +  Vetur：vue开发工具
> 改开发工作具体使用：百度一下，你就知道

### 环境准备

名称：`node.js 以及 npm`

下载地址：<https://nodejs.org/en/download/> 

 + 简单的说 Node.js 就是运行在服务端的 JavaScript。
 + Node.js 是一个基于Chrome JavaScript 运行时建立的一个平台。
 + Node.js是一个事件驱动I/O服务端JavaScript环境，基于Google的V8引擎，V8引擎执行Javascript的速度非常快，性能非常好。

NPM是随同NodeJS一起安装的包管理工具，能解决NodeJS代码部署上的很多问题，常见的使用场景有以下几种：

+ 允许用户从NPM服务器下载别人编写的第三方包到本地使用。
+ 允许用户从NPM服务器下载并安装别人编写的命令行程序到本地使用。
+ 允许用户将自己编写的包或命令行程序上传到NPM服务器供别人使用。

> 由于新版的nodejs已经集成了npm，所以之前npm也一并安装好了。


```
 // 如果出现了版本提示表示安装成功
 npm -v 

 //更新npm
 npm install npm -g 

 //使用淘宝镜像的命令（推荐使用，因npm是国外的，安装插件比较慢）
 npm install -g cnpm --registry=https://registry.npm.taobao.org 

```

### UI库 - ElementUI

官方地址：<https://element.eleme.cn/#/zh-CN/component/installation>


### vue全家桶

官网地址：<https://cn.vuejs.org/>

### 学习项目 - 租户管理后台

项目地址：<http://192.168.1.40:7070/repositories/>

对应版本库：`authority`

> 克隆至本地后，再另起分支进行开发，dev分支（正式版本代码）下面的代码勿动；项目启动在环境搭建好之后，请参照 README.md，执行对应的脚本命令即可。