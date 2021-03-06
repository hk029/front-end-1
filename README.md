# 目录

## 1. 前端基础知识
  * 1.1 从浏览器说起
    * [主流浏览器简介](./basis/basis/browser.md)
    * [浏览器内核简介](./basis/basis/core.md)
    * [页面解析原理与流程](./basis/basis/parse.md)
  * 1.2 HTML
    * [HTML语义化](./basis/html/semantic.md)
    * [HTML常用标签](./basis/html/tag.md)
    * [HTML5增强的表单元素](./basis/html5/form.md)
    * [Doctype与文档模式](./basis/html/doctype.md)
    * [常见头标签](./basis/html/head.md)
  * 1.3 CSS
    * [盒子模型](./basis/css/box.md)
    * [文档流](./basis/css/)
    * [样式优先级](./basis/css/cascade.md)
    * [CSS选择器](./basis/css/css-selector.md)
    * [认识hack](./basis/css/hack.md)
    * [web字体与文本](./basis/css/font.md)
    * [display属性](./basis/css/display.md)
    * [flex布局](./basis/css/flex.md)
    * css黑魔法
      * [表单美化技巧](./basis/css/form-beautify.md)
      * [移入移出效果](./basis/css/hover.md)
    * css预编译
      * [sass](./basis/css/sass.md)
      * [compass](./basis/css/campass.md)
      * [less](./basis/css/less.md)
  * 1.4 网络
    * [TCP](./basis/network/tcp.md)
    * [DNS](./basis/network/dns.md)
    * [HTTP](./basis/network/http.md)
    * [移动网络](./basis/network/mobile-network.md)
  * 1.5 安全知识
    * [客户端的JavaScript限制](./basis/security/restriction.md)
    * [同源策略](./basis/security/same-origin.md)
    * [XSS](./basis/security/xss.md)
    * [CSP](./basis/security/csp.md)
  * 1.6 图片
    * [图片基础概念](./basis/img/img-basis.md)
    * [图片格式](./basis/img/pic-format.md)
    * [base64](./basis/img/base64.md)
    * [webp](./basis/img/webp.md)
  * 1.7 缓存概述
    * [Web缓存概述](./basis/cache/cache.md)
  * 1.8 Mobile Web
    * [像素基础](./basis/mobile/px.md)
    * [viewport](./basis/mobile/viewport.md)
    * [移动布局](./basis/mobile/layout.md)
    * [特殊样式处理](./basis/mobile/style.md)
    * [交互](./basis/mobile/interaction.md)
    * [字体](./basis/mobile/font.md)
  * 1.9 Hybrid
    * [Web APP](./basis/hybrid/webapp.md)
    * [WebView基本介绍](./basis/hybrid/webview.md)
    * [JsBridge](./basis/hybrid/jsbridge.md)
    * [WebView常用设置](./basis/hybrid/webview-advanced.md)
## 2. JavaScript
  * 2.1 数据类型
    * [基本类型与包装类](./javascript/type/basis.md)
    * [类型转换](./javascript/type/transform.md)
    * [类型检测](./javascript/type/is-type.md)
    * [String类型](./javascript/type/string.md)
    * [undefined的冷知识](./javascript/type/undefined.md)
    * [Blob]()
    * [ArrayBuffer]()
  * 2.2 操作符
    * [优先级](./javascript/operator/priority.md)
    * [==运算符](./javascript/operator/equals.md)
  * 2.3 数组
    * [数组基本操作](./javascript/array/array-basis.md)
    * [数组去重](./javascript/array/unique.md)
    * [数组反转](./javascript/array/reverse.md)
    * [数组合并](./javascript/array/merge.md)
  * 2.4 正则表达式
    * [正则表达式速查表](./javascript/regexp/quick-look.md)
    * [RegExp对象](./javascript/regexp/regexp-basis.md)
    * [正则表达式进阶](./javascript/regexp/regexp-advanced.md)
    * [常用正则表达式](./javascript/regexp/practice.md)
  * 2.5 核心概念
    * [作用域](./javascript/core/scope.md)
    * [原型链](./javascript/core/prototype-chain.md)
    * [闭包](./javascript/core/closure.md)
    * [this](./javascript/core/this.md)
    * [函数式编程](./javascript/core/functional-programming.md)
    * [事件循环机制](./javascript/core/event-loop.md)
    * [内存管理](./javascript/core/memory.md)
  * 2.6 高级技巧
    * [安全的构造函数](./javascript/skill/safe-constructor.md)
    * [高级定时器](./javascript/skill/timer.md)
    * [函数节流](./javascript/skill/throttle.md)
    * [函数作用域绑定](./javascript/skill/bind.md)
    * [函数柯里化](./javascript/skill/curry.md)
    * [惰性加载](./javascript/skill/lazy-function.md)
    * [yielding processes](./javascript/skill/yielding-processes.md)
  * 2.7 es6
    * [默认参数](./javascript/es6/default-parameters.md)
    * [模版](./javascript/es6/template.md)
    * [多行字符串](./javascript/es6/multiline-string.md)
    * [解构赋值](./javascript/es6/destructuring-assignment.md)
    * [增强的对象文本](./javascript/es6/enhanced-object-literals.md)
    * [箭头函数](./javascript/es6/arrow-function.md)
    * [promise](./javascript/es6/promise.md)
    * [generator](./javascript/es6/generator.md)
    * [thunk](./javascript/es6/thunk.md)
    * [块级作用域和常量](./javascript/es6/let-const.md)
    * [class](./javascript/es6/class.md)
    * [module](./javascript/es6/module.md)
## 3. 客户端编程
  * 3.1 DOM
    * [概述](./browser/dom/dom-basis.md)
    * [节点类型](./browser/dom/node.md)
    * [元素集合对象](./browser/dom/collection.md)
    * [document对象](./browser/dom/document.md)
    * [选择器](./browser/dom/selectors.md)
    * [节点遍历](./browser/dom/traversal.md)
    * [节点属性操作](./browser/dom/attribute.md)
    * [元素的内容](./browser/dom/innerContent.md)
    * [创建、插入和删除节点](./browser/dom/dom-operation.md)
    * [元素大小与坐标计算]()
  * 3.2 表单
    * [表单基础知识](./browser/form/form-basis.md)
    * [表单的重复提交问题](./browser/form/form-submit.md)
    * [表单类型详述](./browser/form/form-type.md)
    * [表单校验](./browser/form/validate.md)
    * [表单序列化](./browser/form/serialize.md)
    * [FormData对象](./browser/form/formdata.md)
  * 3.3 CSS操作
  * 3.4 事件系统
    * [事件基础概述](./browser/event/event-basis.md)
    * [事件类型](./browser/event/event-type.md)
    * [event对象](./browser/event/event-properties.md)
    * [跨浏览器的事件处理程序](./browser/event/event-listener.md)
    * [事件触发](./browser/event/event-trigger.md)
    * [事件委托](./browser/event/event-delegate.md)
  * 3.5 AJAX
    * [JSON](./browser/ajax/json.md)
    * [XMLHttpRequest](./browser/ajax/xhr.md)
    * [jsonp](./browser/ajax/jsonp.md)
    * [图像Ping](./browser/ajax/ping.md)
    * [Comet](./browser/ajax/comet.md)
    * [websocket](./browser/ajax/websocket.md)
  * 3.6 图片
    * [图片上传方式](./browser/img/upload.md)
    * [图片预加载](./browser/img/preload.md)
    * [图片懒加载](./browser/img/lazyload.md)
  * 3.7 离线缓存与存储
    * [离线检测](./browser/cache/detection.md)
    * [应用缓存](./browser/cache/manifest.md)
    * [cookie](./browser/cache/cookie.md)
    * [web storage](./browser/cache/storage.md)
  * 3.8 历史记录管理
    * [常见API简介]()
    * [导航技术]()
    * [简单的Router]()
  * 3.9 异常处理
  * 3.10 文件操作
## 4. 工具
  * [4.1 emmet](./tools/emmet.md)
  * [4.2 visual studio code](./tools/vscode.md)
  * [4.3 常用git指令](./tools/git.md)
  * [4.4 github的mardown语法](./tools/github-markdown.md)
  * [4.5 github中表情符号指南](./tools/github-emoji.md)
  * 4.6 chrome dev tools
    * [debug](./tools/chrome/debug.md)
    * [timeline](./tools/chrome/timeline.md)
    * [profile]()
    * [移动端页面远程调试](./tools/chrome/mobile-debug.md)
  * 4.7 vim
    * [curl](./tools/vim/curl.md)
    * [bundle](./tools/vim/bundle.md)
    * [vim概述与配置](./tools/vim/vim-basis.md)
    * [vim命令与快捷键](./tools/vim/vim-cmd.md)
    * [vim下的emmet](./tools/vim/vim-emmet.md)
## 5. 前端进阶知识
  * [5.1 渲染性能优化](./advanced/paint-performance.md)
  * [5.2 模块简易管理](./advanced/module.md)
  * [5.4 雅虎性能优化军规](./advanced/yahoo.md)
  * 5.3 设计模式
    * [5.3.1 设计模式简介](./advanced/design-pattern/introduction.md)
    * [5.3.2 Constructor(构造器)模式](./advanced/design-pattern/constructor.md)
    * [5.3.3 Module(模块)模式](./advanced/design-pattern/module.md)
    * [5.3.4 Singleton(单例)模式](./advanced/design-pattern/singleton.md)
    * [5.3.5 Observer(观察者)模式](./advanced/design-pattern/abserver.md)
    * [5.3.6 Publish/Subscribe(发布/订阅)模式](./advanced/design-pattern/pub-sub.md)
    * [常用的设计模式](./advanced/design-pattern/design-pattern.md)
  * 5.4 [webkit](./webkit/introduction.md)
    * [5.4.1 浏览器和内核常识](./webkit/browser.md)
    * [5.4.2 HTML解析渲染过程简介](./webkit/html.md)
## 6. 库与框架
  * [6.1 jQuery](./framework/jquery/introduction.md)
    * [事件API](./framework/jquery/event.md)
    * [常用技巧](./framework/jquery/skill.md)
    * [AJAX](./framework/jquery/ajax.md)
  * [6.2 React](./framework/react/introduction.md)
    * [官方教程示例解析](./framework/react/react-tutorial.md)
    * [Thinking in React](./framework/react/thinking-in-react.md)
    * [jsx](./framework/react/react-jsx.md)
    * [组件](./framework/react/react-component.md)
    * [数据流](./framework/react/react-dataflow.md)
  * 6.3 fastclick
    * [fastclick代码全注释](./framework/fastclick/fastclick-sourcecode.md)
    * [fastclick原理解析](./framework/fastclick/fastclick-principle.md)
  * 6.4 mocha & chai
    * [mocha安装](./framework/mocha/installation.md)
    * [mocha简介](./framework/mocha/introduction.md)
  * 6.5 QUnit
    * [QUnit Cookbook](./framework/qunit/cookbook.md)
  * 6.6 jsdeferred
    * [jsdeferred源码解析](./framework/jsdeferred/sourcecode.md)
## 7. 数据结构与算法基础
  * [7.1 链表](./datastructure/linked-list.md)
  * [7.2 队列与栈](./datastructure/queue-stack.md)
  * 7.3 map
  * 7.4 树
  * 7.5 图
  * 7.6 排序
    * [排序算法概述]()
    * [冒泡排序]()
    * [选择排序]()
    * [快速排序]()
    * [堆排序]()
    * [归并排序]()
## 8. 面试题
  * [8.1 7个去伪存真的JavaScript面试题](./interview/1.md)
  * [8.2 一道常被人轻视的前端JS面试题](./interview/2.md)
  * [8.3 Front End Developer Questions](./interview/3.md)
  * [8.4 前端知识点回顾](./interview/4.md)
  * [8.5 关于for()的一个小知识点](./interview/5.md)
  * [8.6 被问得最多的十个JavaScript前端面试问题](./interview/6.md)
  * [8.7 前端面试题集锦及答案](./interview/7.md)
  * [8.8 2015奇虎360面试题](./interview/8.md)
  * [8.9 BAT2014前端笔试面试题：HTML/CSS篇](./interview/9.md)
  * [8.10 2016年Web前端面试题目汇总](./interview/10.md)
  * [8.11 BAT2014前端笔试面试题：初级JavaScript篇](./interview/11.md)
  * [8.12 BAT2014前端笔试面试题：中级Javascript篇](./interview/12.md)
  * [8.13 JavaScript问题集锦 #2【难度比较大】](./interview/13.md)
  * [8.14 2014阿里前端笔试题：JavaScript篇](./interview/14.md)
  * [8.15 2014阿里前端笔试题：HTML/CSS篇](./interview/15.md)
## 附录
* [附录A: 书单](./appendix/books.md)
* [附录B: 常用网站](./appendix/websites.md)
* [附录C: 我的代码库](https://github.com/zhangguixu/code)
