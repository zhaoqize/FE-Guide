## 一、书籍篇(基础)
1.[JavaScript权威指南](http://note.youdao.com/noteshare?id=b6f02ed9c2c6abff05bd9c70fc8cd197&sub=42E4712CF7304F6883F26749085362DD)

2.[CSS权威指南](http://note.youdao.com/noteshare?id=cb71b0f276145a64dc79acac8d470c19&sub=419E25D845084C7EA6B1C2D63675495E)

3.HTML5权威指南

## 二、书籍篇(进阶)
1.Javascript高级编程设计

2.[锋利的jQUery](http://note.youdao.com/noteshare?id=0dab9597b5123fce772d3bb6d0594d31&sub=83908E5D2A4B4EE9A16828A7A92390D9)

3.[悟透Javascript](http://note.youdao.com/noteshare?id=9ff0a6cfae213546633f6ad192b378a7&sub=E4675C4855274A4899877963EE1F49A8)

4.[CSS揭秘](http://note.youdao.com/noteshare?id=3d6f7be65e989692b9106f7ea3c82653&sub=E96D5D08A715498D85D0A56E14750D1D)

5.[JavaScript框架设计](http://note.youdao.com/share/?id=1ff646f8d43840385c15be1bc7b01837&type=note#/)

6.[Web性能权威指南](http://note.youdao.com/noteshare?id=11bce06160006a71e2cdab2aed90bc0b&sub=D68EF671B4A842DE846985EF880066C4)

7.[Javascript数据结构与算法](http://note.youdao.com/noteshare?id=763ef67893b37739686e57f51aa4130d&sub=889BE82BC97B4B29AB29D80EE5CA7FDC)

8.[编写可维护的Javascript](http://note.youdao.com/noteshare?id=06108a830b22cafcec30db5446c4bd01&sub=285DB98C19DF4D6085146C37AD27FB7A)

9.[Web前端黑客技术揭秘](http://note.youdao.com/noteshare?id=9d75c42a4d58763e52d028a3921b0b6e&sub=WEB13ce6c4a435c9d543ea77e0569dd2cbe)

10.[HTTP权威指南](http://note.youdao.com/noteshare?id=820e4e06cb76515b777795da8a1a70b0&sub=6E691A6885A34859BAF637252C6469F0)

11.[Javascript函数式编程](http://note.youdao.com/noteshare?id=bb9ca71251d184b0fad776bbe217a2e8&sub=4FB94CE55A2542358BFA2EA0BD120408)

## 三、NodeJs书籍
1.[NodeJs手册](http://note.youdao.com/noteshare?id=7f0fadee2ba1bbeffde9d99ecd1f3e5a&sub=973E52D1D16A4FA088083B02ADB64C52)

2.[NodeJs开发指南](http://note.youdao.com/noteshare?id=69c672d4b0d61032d162bde2339e7d09&sub=689A58814F414E6EB05240BC4FE4D520)

3.[NodeJs](http://note.youdao.com/noteshare?id=d10cbdb5e5b18b7bae040f71c862a8fc&sub=0E2E48E3C8F34BA6A038E72A21BD6209)

4.NodeJs的深入浅出

5.NodeJs与Express开发
## 前端页面开发的正确姿势


## 模板引擎
1.Jade(Pug)

Jade是一种服务端的模板引擎，常见于nodejs的项目中，还有一个是ejs。

Jade通过缩进来控制台层级关系。

大体的样子:
```jade
.wb-funtime
  .wb-title-side
    a(target='_blank', href='') demo
  .wbf-main
    ul.wbf-ul.clearfix
      -for(var i=0;i<funTime.length;i++){
       
      -}
```
学习资料:

[Jade模板引擎让你飞](http://www.cnblogs.com/zqzjs/p/6057254.html)

2.Handlebars

Handlebars是前端模板引擎。

学习资料:

[Handlebars模板引擎之上手](http://www.cnblogs.com/zqzjs/p/6233153.html)

[Handlebars模板引擎之上手](http://www.cnblogs.com/zqzjs/p/6233444.html)

[Handlebars模板引擎之上手](http://www.cnblogs.com/zqzjs/p/6233479.html)

## UI

1.Bootstrap 一个经典的前端UI框架

2.material-ui 一个基于谷歌设计语言material design的UI库
## 前端工程

### 预编译
1.Less

可以使用koala工具来实时编译

2.Sass

3.TypeScript

### 构建工具
### Gurnt

老牌的前端构建工具

### Gulp

想要替代grunt的构建工具，是grunt的升级版。

### Fis3

一个百度开发的构建工具

### Webpack

现在比较火的构建工具，与react,vue结合做单页面开发较多。

1.webpack

2.webpack-dev-server

### 单元测试
1.Mocha

mocha是一个单元测试框架，可以配合各种断言库，比如chai。小巧，轻量。

2.Chai

chai是一个用来断言的库

3.Rewire

rewire是一个用来返回模块中所有私有方法与变量的库

4.Istanbul

istanbul用来测试代码覆盖率

### 持续集成
1.Travis CI

现在一个比较火的在线持续集成的工具，github完美使用。

## React篇
### es6

1.[阮一峰es6](http://es6.ruanyifeng.com/)

### Babel
babel是用来将es6,es7,next的新语法转为浏览器可以执行的Javascript。

需要配置的依赖包:

1.babel-core

2.babel-loader

3.babel-plugin-transform-decorators-legacy //es7语法

4.babel-preset-es2015

5.babel-preset-react

3.babel-preset-stage-1
### JSX

### 常用库
1.react
    
2.react-dom

3.react-router

4.isomorphic-fetch

方便用来做同构

5.whatwg-fetch

### 状态管理
### Redux
1.react-redux

2.react-router
### Mobx
1.mobx-react

### Dva
阿里的react+redux的框架

[dva](https://github.com/dvajs/dva/blob/master/README_zh-CN.md)

## React+Redux的理解
[React + Redux 最佳实践](https://github.com/sorrycc/blog/issues/1)

[支付宝前端应用架构的发展和选择](https://github.com/sorrycc/blog/issues/6)

## NodeJs篇

### 框架
1.Express

2.Koa

### 开发必备库
1.[node-supervisor](https://github.com/petruisfan/node-supervisor)

A little supervisor script for nodejs.

2.[node-inspector](https://github.com/node-inspector/node-inspector)

Node.js debugger based on Blink Developer Tools

3.[node-formidable](https://github.com/felixge/node-formidable)

A node.js module for parsing form data, especially file uploads.

4.[pm2](https://github.com/Unitech/pm2)

Production process manager for Node.js apps with a built-in load balancer

5.[forever](https://github.com/foreverjs/forever)

A simple CLI tool for ensuring that a given script runs continuously

6.[node-schedule](https://github.com/node-schedule/node-schedule)

A cron-like and not-cron-like job scheduler for Node.

7.[mysql](https://github.com/mysqljs/mysql)

A pure node.js JavaScript Client implementing the MySql protocol.

8.[log4js](https://github.com/nomiddlename/log4js-node)

A port of log4js to node.js

9.[bluebird](https://github.com/petkaantonov/bluebird)

Bluebird is a full featured promise library with unmatched performance. 

10.[nodemailer](https://github.com/nodemailer/nodemailer)

:email: Send e-mails with Node.JS – easy as cake!

### 有待商榷的库
#### orm
1.node-orm2

2.sequelize

## 开发平台篇
1.Windows

2.Ubuntu

3.CentOS

## 桌面应用开发
### NW.js

nw.js是一个老牌的使用前端技术开发桌面应用的先驱。

### Electron

electron是一个现在非常流行的一个桌面应用开发库，从2016年中旬有点苗头，到2017年1月份这段时间发展很快。

## 微信公众号开发


## 工具篇
### 开发辅助工具
1.Beyond Compare 4

文件比对工具

2.Xshell5

3.Wamp

服务全家桶

4.FastStone Capture

截图软件

5.mark Main

页面标注工具

6.PS

7.FileZilla
### chrome浏览器应用
1.Notty Notes 

用来在chrome浏览器中添加书签的

2.Adblock

拦截，过滤网页广告

3.Bookmark Manager

书签管理器

4.Axure RP Extension for Chrome

原型设计工具

5.JSONView

页面数据JSON化显示

6.Postman


7.React Developer Tools

React开发调试工具

8.Vue.js devtools

Vue开发调试工具
9.YSlow

谷歌页面性能分析工具

10.掘金

掘金谷歌应用版

11.马克飞象

12.Octotree

### 编辑器
1.sublime

2.xcode

3.atom

### windows下的cmd
1.cmder

### 统计时间
1.WakeTime

### 翻译

1.有道词典：作为我们常用的翻译文章单词的随手工具是必不可少的利器。

技巧：快捷键设置：可以随时想用的的时候调用起程序。
