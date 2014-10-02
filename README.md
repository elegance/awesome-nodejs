# Awesome Node.js
# 精彩的Node.js

受到[精彩的php](https://github.com/ziadoz/awesome-php) 和 [精彩的python](https://github.com/vinta/awesome-python) 的启发，整理了精彩的Node.js的框架，库以及资源的列表。

欢迎提交各种相关资源！让我们一起来打造最精彩的Node资源列表！

目录:

- [精彩的Node.js](#awesome-nodejs)
    - [环境管理](#environment-management)
    - [桌面应用](#desktop-app)
    - [集成开发环境](#integrated-development-enviroments)
    - [文档](#documentation)
    - [包管理](#package-management)
    - [生成工具](#build-tools)
    - [通讯](#communication)
    - [数据库驱动](#database-drivers)
    - [调试工具](#debugging-tools)
    - [日志](#logging)
    - [ORM](#orm)
    - [Web框架](#web-frameworks)
    - [应用服务](#application-servers)
    - [CMS](#content-management-system)
    - [RESTful API](#restful-api)
    - [文件和MIME类型操作](#files-and-mime-type-manipulation)
    - [验证和OAuth](#authentication-and-oauth)
    - [模版引擎](#template-engine)
    - [生成CLI的工具](#tools-for-building-clis)
    - [异步流程控制](#async-control-flow)
    - [测试](#testing)
- [其它精彩列表](#other-awesome-lists)

## Environment Management
## 环境管理

*Libraries for Node version and environment management.*

*管理Node版本和环境的库*

* [nodeenv](https://github.com/ekalinin/nodeenv) - Virtual environment for Node.js & integrator with virtualenv.

    独立的Node.js运行环境(Python写，未使用过)

* [nave](https://github.com/isaacs/nave) - Virtual Environments for Node.

    似乎不错(sh脚本，未使用过)

* [n](https://github.com/visionmedia/n) - Node version management.

    安装不同版本的node，可以多个版本的node并存
    
## Desktop App
## 桌面应用

* [atom-shell](https://github.com/atom/atom-shell) -
可以使用nodejs编写桌面应用，并且跨平台，支持mac，linux，windows，与[node-webkit](https://github.com/rogerwang/node-webkit)的区别在于，前者启动时是启动js文件，后者启动html文件，前者可控性更高。

node-webkit案例:[LightTable](https://github.com/LightTable/LightTable)
atom-shell案例:[Atom](https://github.com/atom/atom)


## Integrated Development Enviroments
## 集成开发环境

*IDEs and Editors for development*

* [Enide](http://www.nodeclipse.org/enide/) - Node Eclipse IDE with Nodeclipse plugin.
* [InteliJIDEA](http://www.jetbrains.com/idea/features/nodejs.html) - Fast Node plugin for InteliJ.
* [Webstorm](http://www.jetbrains.com/webstorm/features/#node.js) - "Create great websites and applications in a great IDE. The best JavaScript IDE and HTML editor is at your service."
* [Atom](https://github.com/atom/atom) - The hackable editor by GitHub
* [Brackets](https://github.com/adobe/brackets) - An open source code editor for the web, written in JavaScript, HTML and CSS.
* [Cloud9](https://c9.io/site/code-smarter-code-together/) - Web editor with collaboration tools.
* [Notepad++](http://notepad-plus-plus.org) - Notepad++ is a free source code editor and Notepad replacement that supports several languages.
* [CmdEr](https://github.com/bliker/cmder) - Not really and IDE, but a great "lovely console emulator package for Windows"

## Documentation
## 文档

*Libraries for generating project documentation.*

* [Docco](http://jashkenas.github.io/docco/) - Docco is a quick-and-dirty documentation generator, written in Literate CoffeeScript.
* [Groc](https://github.com/nevir/groc) - Documentation generation, in the spirit of literate programming.
* [dox](https://github.com/visionmedia/dox) - JavaScript documentation generator for node using markdown and jsdoc.

## Package Management
## 包管理

*Libraries for package and dependency management.*

* [Npm](https://www.npmjs.org/) - Default package manager. Installs, publishes and manages node programs.

## Build Tools
## 生成工具

*Libraries for building and task running*

* [Gulp.js](http://gulpjs.com/) - A streaming build system which use of streams and code-over-configuration.
* [Grunt.js](http://gruntjs.com/) - A task runner to ease epetitive tasks like unit testing, compilation and so on.
* [Nodemon](http://nodemon.io/) - A dev utility that monitor any changes in source and automatically restart server.

## Communication
## 通讯

* [Socket.IO](http://socket.io/) - Websocket framework for Node and Javascript.
* [Primus](https://github.com/primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in.

## Database Drivers
## 数据库驱动

*Libraries for connecting and operating databases*

* [Node-mysql](https://github.com/felixge/node-mysql/) - A pure node.js JavaScript Client implementing the MySql protocol.
* [Node-mongodb-native](https://github.com/mongodb/node-mongodb-native/) - Mongo DB Native NodeJS Driver.

## Debugging Tools
## 调试工具

*Tools for debugging Node applications*

* [node-inspector](https://github.com/node-inspector/node-inspector) - Node.js debugger based on Blink Developer Tools.
* [longjohn](https://github.com/mattinsler/longjohn) - Longer stack traces for Node.
* [TypesJs](https://github.com/ChrisAntaki/typesjs) - Easy type checking, for Node & browsers.

## Logging
## 日志

*Tools for generating and working with log files.*

* [caterpillar](https://github.com/bevry/caterpillar) - A logging system that can log and pipe the output off to different locations.
* [tracer](https://github.com/baryon/tracer) - A powerful and customizable logging library for node.js.
* [Log.io](http://logio.org/) - Real time logging facility on the browser.

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [Sequelize](http://sequelizejs.com/) - Sequelize library provides easy access to MySQL, MariaDB, SQLite or PostgreSQL databases.
* [Node-orm2](https://github.com/dresende/node-orm2) - Another Relational Object Mapper.
* [Mongoose](http://mongoosejs.com/) - Almost an ORM for mongodb.

## Web Frameworks
## Web框架

*Web development frameworks.*

* [Express](http://expressjs.com/) -  A minimal and flexible node.js web application framework.
* [Flatiron](http://flatironjs.org/) - An adaptable framework for building modern web applications.
* [Koa](http://koajs.com/) - A framework which aims to be a smaller, more expressive, and more robust foundation for web applications.
* [Totaljs](http://www.totaljs.com/) - Friendly responsive design web application framework for node.
* [Meteor](https://www.meteor.com/) - A platform that has strong features such as live page update, sync and hopt code pushes.
* [Hapi](https://github.com/spumko/hapi) - A rich framework for building applications and services.

## Application Servers
## 应用服务

*Application Server is an environment to run and manage multiple applications.*

* [Impress](https://github.com/tshemsedinov/impress) - Impressive multipurpose scalable Application Server optimized for high load API and web applications.

## Content Management System
## CMS

* [Calipso](http://calip.so/) - Calipso is a simple CMS, built along similar themes to Drupal and Wordpress.

## RESTful API

*Libraries for developing RESTful APIs.*

* [Sails](http://sailsjs.org) - MVC framework which generates a RESTful JSON API.
* [Node-restify](http://mcavage.me/node-restify/) - A node.js module built specifically to build correct REST web services.
* [Heimdall](https://github.com/binarymax/heimdall) - REST API Guardian for Express.

## Files and MIME Type Manipulation
## 文件和MIME类型操作

* [PDFKit](http://pdfkit.org/) - A JavaScript PDF generation library for Node and browser.

## Authentication and OAuth
## 验证和OAuth

*Libraries for implementing authentications schemes.*

* [PassportJS](http://passportjs.org/) - Simple authentication middleware framework.
* [ldapjs](http://ldapjs.org/) - Pure JavaScript, from-scratch framework for implementing LDAP clients and servers.

## Template Engine
## 模版引擎

*Libraries and tools for templating and lexing.*

* [ECT](http://ectjs.com/) - "Fastest JavaScript template engine with embedded CoffeeScript syntax" as they say (benchmark proof).
* [Jade](http://jade-lang.com/) - Handful node template engine.
* [Swig](http://paularmstrong.github.io/swig/) - A simple, powerful, and extendable JavaScript Template Engine.

## Tools for building CLIs
## 生成CLI的工具

*Libraries and tools which support you by building Command-Line Interfaces.*

* [Inquirer](https://github.com/SBoudrias/Inquirer.js) - A collection of common interactive command line user interfaces. *Ask questions, parsing, validating answers, managing hierarchical prompts and providing error feedback.*
* [commander.js](https://github.com/visionmedia/commander.js) - The complete solution for node.js command-line interfaces, inspired by Ruby's commander.
* [cli-table](https://github.com/LearnBoost/cli-table) - Pretty unicode tables for the CLI with Node.JS
* [blessed](https://github.com/chjj/blessed) - A curses-like library for node.js.
* [chalk](https://github.com/sindresorhus/chalk) - Terminal string styling done right
* [minimist](https://github.com/substack/minimist) - Simple module for command line arguments parsing.
* [read](https://github.com/isaacs/read) - For reading user input from stdin.
* [colors.js](https://github.com/Marak/colors.js) - get colors in your node.js console like what.
* [configstore](https://github.com/yeoman/configstore) - Easily load and persist config without having to think about where and how.
* [blessed](https://github.com/chjj/blessed) - A curses-like library for node.js.
* [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels.https://github.com/sindresorhus/log-symbols
* [terminal-menu](https://github.com/substack/terminal-menu) - retro ansi terminal menus for serious 80s technicolor business.
* [cli-spinner](https://github.com/helloIAmPau/node-spinner) - A simple spinner for node cli.
* [text-table](https://github.com/substack/text-table) - generate borderless text table strings suitable for printing to stdout.

## Async Control Flow
## 异步流程控制

*Libraries, that help you manage asyncronous control flow and avoid callback hell.*

* Callback-based:
    * [Async](https://github.com/caolan/async) - Utility module which provides straight-forward, powerful functions for working with asynchronous JavaScript.
* Promise-based ([Promises/A+](http://promises-aplus.github.io/promises-spec/)):
    * [Q](https://github.com/kriskowal/q) - Full-featured promise library with large API covering any situation you may encounter.
    * [RSVP.js](https://github.com/tildeio/rsvp.js) - Lightweight, but still compliant, promise library.
    * [when.js](https://github.com/cujojs/when) - Rock solid, battle tested promise library.
    * [Bluebird](https://github.com/petkaantonov/bluebird) - Bluebird is a fully featured promise library with focus on innovative features and performance.
* Fibers-base ([node-fibers](https://github.com/laverdet/node-fibers/)):
    * [asyncawait](https://github.com/yortus/asyncawait) - Inspired by C# async/await feature, implementation of the same patter using fibers.
* Generator-based:
    * [Co](https://github.com/visionmedia/co) - Generator based flow-control goodness for nodejs and the browser.

## Testing
## 测试

*Testing frameworks.*

* [mocha](https://github.com/visionmedia/mocha) - Mocha is a feature-rich JavaScript test framework running on node.js and the browser, making asynchronous testing simple and fun.
* [tape](https://github.com/substack/tape) - tap-producing test harness for node and browsers.
* [should.js](https://github.com/visionmedia/should.js) - BDD style assertions for node.js -- test framework agnostic.
* [chai](https://github.com/chaijs/chai) - BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework.

# Other Awesome Lists
# 其它精彩列表
Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

# Contributing

Your contributions are always welcome!
