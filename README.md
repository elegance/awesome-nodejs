# 精彩的Node.js

受到[精彩的php](https://github.com/ziadoz/awesome-php) 和 [精彩的python](https://github.com/vinta/awesome-python) 的启发，整理了精彩的Node.js的框架，库以及资源的列表。

欢迎提交各种相关资源！让我们一起来打造最精彩的Node资源列表！

目录:

- [精彩的Node.js](#精彩的Nodejs)
    - [环境管理](#环境管理)
    - [桌面应用](#桌面应用)
    - [集成开发环境](#集成开发环境)
    - [文档](#文档)
    - [包管理](#包管理)
    - [生成工具](#生成工具)
    - [通讯](#通讯)
    - [调试工具](#调试工具)
    - [日志](#日志)
    - [数据库驱动](#数据库驱动)
    - [ORM](#orm)
    - [Web框架](#web框架)
    - [RESTful API](#restful-api)
    - [应用服务](#应用服务)
    - [CMS](#cms)
    - [表单](#表单)
    - [文件和MIME类型操作](#文件和mime类型操作)
    - [验证和OAuth](#验证和oauth)
    - [模版引擎](#模版引擎)
    - [生成CLI的工具](#生成cli的工具)
    - [异步流程控制](#异步流程控制)
    - [Rate Limiting](#rate-limiting)
    - [测试](#测试)
    - [杂项](#杂项)
- [其它精彩列表](#其它精彩列表)

## 环境管理

*Node虚拟机*

* [nodeenv](https://github.com/ekalinin/nodeenv) - Node.js的虚拟环境,提供独立的Node.js运行环境(Python)
* [nave](https://github.com/isaacs/nave) - Node的虚拟环境(sh脚本)

*Node版本管理*

* [n](https://github.com/visionmedia/n) - Node版本管理，可以安装不同版本的node，可以多个版本的node并存
* [nvm](https://github.com/creationix/nvm) - Node版本管理器(不用装node即可使用).

*[n vs nvm](http://www.mattpalmerlee.com/2013/03/23/installing-and-switching-between-multiple-versions-of-node-js-n-vs-nvm/)个人喜欢：n
    
## 桌面应用

* [Atom Shell](https://github.com/atom/atom-shell) -
可以使用nodejs编写桌面应用，并且跨平台，支持mac，linux，windows，与[node-webkit](https://github.com/rogerwang/node-webkit)的区别在于，前者启动时是启动js文件，后者启动html文件，前者可控性更高。

node-webkit案例:[LightTable](https://github.com/LightTable/LightTable)
atom-shell案例:[Atom](https://github.com/atom/atom)


## 集成开发环境

*开发用的IDE和编辑器*

* [Webstorm](http://www.jetbrains.com/webstorm/features/#node.js) - 最好的Nodejs编辑器，有的话就不用看下面这些了。
* [Visual Studio](http://www.visualstudio.com/) - 需要安装插件 [Node.js Tools for Visual Studio](https://nodejstools.codeplex.com/) (支持编辑，智能感知，分析，npm，TypeScript，本地调试以及Windows/MacOS/Linux上的远程调试)。
* [Enide](http://www.nodeclipse.org/enide/) - 带Nodeclipse插件的Node Eclipse IDE。
* [InteliJIDEA](http://www.jetbrains.com/idea/features/nodejs.html) - InteliJ的Node.js插件，和Webstorm同一家公司出品。
* [Atom](https://github.com/atom/atom) - Github出品的可自定义编辑器(用Atom Shell开发的)。
* [Brackets](https://github.com/adobe/brackets) - 使用JavaScript,HTML,CSS编写的开源web代码编辑器。
* [Cloud9](https://c9.io) - 带协作工具的web编辑器。
* [Notepad++](http://notepad-plus-plus.org) - Notepad++就不用解释了，能用这个写代码的都明白这是什么。
* [CmdEr](https://github.com/bliker/cmder) - 不是IDE，但是Windows上的控制台模拟器（用这个不如安装Github的git shell）。
* [Cloud Commander](http://cloudcmd.io) - Web文件管理。有编辑器和控制台。可以让你开发Web应用，站点等。

## 文档

*项目文档生成库*

* [Docco](http://jashkenas.github.io/docco/) - Docco是一个快速但是丑陋的文档生成器, 由Literate CoffeeScript编写。
* [Groc](https://github.com/nevir/groc) - 以文学编程为宗旨的文档生成器。
* [dox](https://github.com/visionmedia/dox) - JavaScript文档生成器，使用markdown和jsdoc生成node文档。

## 包管理

*包和依赖管理库*

* [Npm](https://www.npmjs.org/) - 默认包管理工具。安装，发布，管理node程序。（必用！识node不识npm犹如识.net不识nuget）
* [Npmsafe](https://github.com/ueqt/npmsafe) - 因为npm安装存在钓鱼的风险，所以用这个库更安全。（必用！）

## 生成工具

*生成和任务执行工具*

* [Gulp.js](http://gulpjs.com/) - 流生成系统，基于流和代码胜于配置。
* [Grunt.js](http://gruntjs.com/) - 任务执行器，可简化单元测试，编译等任务。

*后端Grunt前端Bower，近乎标配，但是google的web starter kit更推荐gulp，因为gulp基于js,grunt基于json，孰优孰劣，可见一斑* 

* [Nodemon](http://nodemon.io/) - 监控代码变化，自动重启服务器的开发工具。
* [Browserify](http://browserify.org/) - Browserify让你可以在浏览器中使用require('modules')来打包你的依赖。

## 通讯

* [Socket.IO](http://socket.io/) - Node和Javascript的Websocket框架。
* [SockJS](https://github.com/sockjs) - Websocket模拟器.
* [Primus](https://github.com/primus/primus) - 阻止模块锁住的实时框架抽象层。
* [BinaryJS](http://binaryjs.com/) - BinaryJS是处理实时二进制数据的二进制webscoket。

## 调试工具

*调试Node应用的工具*

* [node-inspector](https://github.com/node-inspector/node-inspector) - 基于Blink开发工具的Node.js调试器。
* [longjohn](https://github.com/mattinsler/longjohn) - Node的长堆栈跟踪器。
* [TypesJs](https://github.com/ChrisAntaki/typesjs) - Node和浏览器的简易类型检查。
* [Nodev](https://github.com/akamensky/nodev) - 基于nodemon和node-inspector的更方便的调试工具。
* [cf-node-debug](https://www.npmjs.org/package/cf-node-debug) - 用来帮助调试运行在Paas上的node的代理。

## 日志

*生成和管理日志的工具*

* [winston](https://github.com/flatiron/winston) 好用的日志生成库。
* [caterpillar](https://github.com/bevry/caterpillar) - 可以记录日志和输出到不同目标的日志系统。
* [tracer](https://github.com/baryon/tracer) - Node.js的强力和可自定义日志库。
* [Log.io](http://logio.org/) - 浏览器上的实时日志工具。
* [Bunyan](https://github.com/trentm/node-bunyan) - Node.js服务的简单高效JSON日志模块。

## 数据库驱动

*连接和操作数据库的库*

* [Node-mysql](https://github.com/felixge/node-mysql/) - 连接mysql的不二选择。
* [mongojs](https://github.com/mafintosh/mongojs) - 连接mongodb的不二选择，mongoose过于复杂，完全没必要。这个库是基于[Node-mongodb-native](https://github.com/mongodb/node-mongodb-native/)的封装。
* [Node-redis](https://github.com/mranney/node_redis) - Redis驱动，原生解析器用[hideredis](https://github.com/redis/hiredis-node),基于Promise的API用 [then-redis](https://github.com/mjackson/then-redis)。

## ORM

*实现ORM或datamapping技术的库*

* [Sequelize](http://sequelizejs.com/) - 方便地访问MySQL, MariaDB, SQLite 以及PostgreSQL数据库。
* [Node-orm2](https://github.com/dresende/node-orm2) - 另一个ORM。
* [Mongoose](http://mongoosejs.com/) - mongodb的ORM。
* [Waterline](https://github.com/balderdashy/waterline) - 简化多个数据库的交互。

## Web框架

*Web开发框架*

* [Express](http://expressjs.com/) -  小而全的Nodejs web开发框架。主流！但原作者跑去写Go了。
* [Flatiron](http://flatironjs.org/) - 编写现代化web应用的可适配框架。
* [Koa](http://koajs.com/) - 旨在打造更小，更便捷，更高扩展的web应用框架。Express原班人马打造，下一代框架。
* [Totaljs](http://www.totaljs.com/) - 高响应的node web应用框架。
* [Meteor](https://www.meteor.com/) - 实时web应用框架。获得1120万美元风投。未来的框架。
* [Derby](https://github.com/derbyjs/derby) - 方便编写实时应用的MVC框架。
    * [Derby-awesome](https://github.com/onerussell/awesome-derby) - 好用的Derby组件。
* [HuntJS](https://huntjs.herokuapp.com/) - 事件驱动框架。
* [Pomelo](https://github.com/NetEase/pomelo) - 网易出品的Nodejs游戏开发框架。

## RESTful API

*开发RESTful API的库*

* [Hapi](https://github.com/spumko/hapi) - Restful API的快速框架。
    * [hapi-swagger](https://github.com/glennjones/hapi-swagger)生成api文档。
* [Sails](http://sailsjs.org) - 生成RESTful JSON API的MVC框架。
* [Node-restify](http://mcavage.me/node-restify/) - 生成REST web服务的node模块。
* [Heimdall](https://github.com/binarymax/heimdall) - Express的REST API插件。

## 应用服务

*运行和管理多个应用*

* [PM2](https://github.com/Unitech/pm2) - 必用!生产环境中的不二法宝。管理多个node进程，崩溃自动重启，日志查看等功能。
* [Impress](https://github.com/tshemsedinov/impress) - 高负载，可扩展的应用服务。

## CMS

* [Calipso](http://calip.so/) - 简易CMS，类似Drupal和Wordpress的皮肤。
* [KeystoneJS](http://keystonejs.com/) - Node.js CMS，由Express和MongoDB构建的Web应用平台。 

## 表单

*处理表单和表单数据的库*

* [node-validator](https://github.com/chriso/validator.js) - 简易字符串表单验证库。
* [express-validator](https://github.com/ctavan/express-validator) - Express表单验证中间件。

## 文件和MIME类型操作

* [PDFKit](http://pdfkit.org/) - Node和浏览器的JavaScript PDF生成库。

## 验证和OAuth

*实现验证的库*

* [PassportJS](http://passportjs.org/) - 简易验证中间件库。
* [ldapjs](http://ldapjs.org/) - 纯JavaScript框架，用来实现LDAP客户端和服务端。
* [oauth-signature-js](https://github.com/bettiolo/oauth-signature-js) - OAuth 1.0a签名生成器。
* [Lockit](https://github.com/zemirco/lockit) - Express的全功能验证方案。

## 模版引擎

*模版和词法工具*

* [ECT](http://ectjs.com/) - "内嵌CoffeScript语法的快速JavaScript模版引擎。"
* [Jade](http://jade-lang.com/) - node模版引擎。
* [Swig](http://paularmstrong.github.io/swig/) - 简单，强大，易扩展的JavaScript模版引擎。

## 生成CLI的工具

*命令行接口生成工具*

* [Inquirer](https://github.com/SBoudrias/Inquirer.js) - 常用交互命令行用户接口集合。*提问，解析，验证回答，管理提示符以及提供错误反馈。*
* [commander.js](https://github.com/visionmedia/commander.js) - 受Ruby的commander启发的，node.js命令行接口的完整解决方案。
* [cli](https://github.com/chriso/cli) - 可用node快速生成命令行应用。
* [cli-table](https://github.com/LearnBoost/cli-table) - CLI的美化unicode表格。
* [blessed](https://github.com/chjj/blessed) - 一个类似魔咒的node.js类库。
* [chalk](https://github.com/sindresorhus/chalk) - 终端字符串样式。
* [minimist](https://github.com/substack/minimist) - 命令行参数解析简易模块。
* [read](https://github.com/isaacs/read) - 读取用户stdin输入。
* [colors.js](https://github.com/Marak/colors.js) - node.js控制台颜色。
* [configstore](https://github.com/yeoman/configstore) - 简易读取，存储配置。
* [blessed](https://github.com/chjj/blessed) - 一个类似魔咒的node.js类库。
* [log-symbols](https://github.com/sindresorhus/log-symbols) - 不同日志层级不同颜色表示。https://github.com/sindresorhus/log-symbols
* [terminal-menu](https://github.com/substack/terminal-menu) - ansi终端菜单。
* [cli-spinner](https://github.com/helloIAmPau/node-spinner) - 简易的node cli插件。
* [text-table](https://github.com/substack/text-table) - 生成无边框的文本表格字符串用来输出。

## 异步流程控制

*管理异步控制，避免回调地狱*

* 基于回调:
    * [Async](https://github.com/caolan/async) - 直接的，功能强大的异步jas模块。好用！
    * [node-seq](https://github.com/substack/node-seq) - nodejs链式异步流程，并行，以及pipeline式的错误处理。
* 基于Promise ([Promises/A+](http://promises-aplus.github.io/promises-spec/)):
    * [Q](https://github.com/kriskowal/q) - 拥有大量API，包含各种场景的功能完整的promise库。
    * [RSVP.js](https://github.com/tildeio/rsvp.js) - 轻量级，但是可以使用的promise库。
    * [when.js](https://github.com/cujojs/when) - 常用的promise库。
    * [Bluebird](https://github.com/petkaantonov/bluebird) - Bluebird是关注于创新功能和性能的全功能promise库。
* 基于Fibers ([node-fibers](https://github.com/laverdet/node-fibers/)):
    * [asyncawait](https://github.com/yortus/asyncawait) - 参考C#的async/await功能，实现相同的模式。
* 基于生成器:
    * [Co](https://github.com/visionmedia/co) - 基于生成器的流程控制。

## Rate Limiting

*Libraries that help restrict the frequency of certain actions.*

* [Bottleneck](https://github.com/SGrondin/bottleneck) - A powerful rate limiter that makes throttling easy.

## 测试

*测试框架*

* [mocha](https://github.com/visionmedia/mocha) - Mocha是一个运行在node.js上的功能齐全的JavaScript测试框架，使异步测试方便而有趣。
* [tape](https://github.com/substack/tape) - 为node和浏览器定制的测试。
* [should.js](https://github.com/visionmedia/should.js) - nodejs的BDD风格断言。
* [chai](https://github.com/chaijs/chai) - BDD / TDD 断言框架，可与任何其它框架配套使用。
* [sinon](http://sinonjs.org/) - 独立的Javascript测试间谍, stub以及mock。
* [Jasmine](http://jasmine.github.io/) - 简易的Node和Javascript的行为测试。
* [Expresso](http://visionmedia.github.io/expresso/) - Node的TDD框架。
* [NodeUnit](https://github.com/caolan/nodeunit) - 简单语法的单元测试工具。
* [Concrete](http://ryankee.github.io/concrete/) - CI服务。
* [ready.js](http://dsimard.github.io/ready.js/) - javascript CI工具。
* [Jezebel](https://github.com/benrady/jezebel) - Jasmine测试的REPL以及持续集成测试工具。

## 杂项

* [Github Linker](https://chrome.google.com/webstore/detail/github-linker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome扩展，提供github上package.json的依赖库的超链接。


# 其它精彩列表

可以在[awesome-awesome](https://github.com/emijrp/awesome-awesome) 以及 [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) 中找到其它精彩列表。

# 贡献

欢迎您提出宝贵意见和建议！
