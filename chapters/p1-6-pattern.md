# 前端应用的架构与设计模式


## 散弹式架构 -> jQuery

项目达到一定的程度，jQuery 便有些难以管理，我们不知道哪个地方还操作了 DOM。修改了 A 处的 selector，可能会影响 B 处的 selector。

这样的修改方式称为『散弹式架构』，它来自于 散弹式修改（shotgun surgery，出处《重构：改善既有代码的设计》），

在使用 Backbone 的过程中，如果你采用了继承 View 的方式，你也会遇到这种遇到问题。

## 分层结构 MV*

典型的 SPA 应该会具有的模式，如 Angular，Vue.js 

## 处理数据 pipe and filter 

fetch、ajax、RxJS 从 API 处获取到数据 

这个时候的数据首先会被转换为 JSON，再过滤到需要的字段，再对字段进行特殊的处理，如 HtmlEncoded，最后再 Render 到元素上。

当我们从服务器

## 数据显示 观察者模式

双向绑定，即观察者模式，又可以称为发布订阅模式（Publish/Subscribe）

## 数据通讯

除了常规的数据获取，还有在不同的框架间传输数据，如 React Native 和 WebView 的 postMessage，Cordova 的 WebView 与原生插件间

### 消息通讯

### 数据通讯：shared repository

其他消息通讯

### 数据通讯：local storage  

??? black board
