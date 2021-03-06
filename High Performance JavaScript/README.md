# HighPerformanceJavaScript

## 《高性能JavaScript》读书笔记

### 第一章  [加载和执行](./LoadingAndExecution/README.md)
> JavaScript在浏览器中的性能，可以认为是开发者所面临的最重要的可用性问题。这个问题因JavaScript的阻塞特性变得复杂，也就是说当浏览器在执行JavaScript代码时，不能同时做其他任何事情。事实上，大多数浏览器都使用单一进程来处理用户界面（UI）更新和 JavaScript 脚本执行，所以同一时刻只能做其中的一件事情。JavaScript 执行过程耗时越久，浏览器等待响应用户输入的时间就越长。

### 第二章  [数据存取](./DataAccess/README.md)
> 计算机科学中有一个经典问题是通过改变数据的存储位置来获得最佳的读写性能，数据存储的位置关系到代码执行过程中数据的检索速度。

### 第三章  [DOM编程](./DomScripting/README.md)

> 脚本进行DOM操作的代价很昂贵，它是富Web应用中最常见的性能瓶颈。本章将讨论可能对程序造成负面影响的 DOM 编程，并给出提高响应速度的建议。本章讨论以下三类问题：
> * 访问和修改DOM元素
> * 修改DOM元素的样式会导致重绘（repaint）和重排（reflow）
> * 通过DOM事件处理与用户的交互

### 第四章  [算法和流程控制](./AlgorithmsAndFlowControl/README.md)
> 代码的整体结构是影响运行速度的主要因素之一。代码数量少一定运行速度快，代码数量多却也不意味着运行速度一定慢。影响性能的最直接因素是代码的组织结构，以及具体问题的解决方法。

> 本章讨论的技术并不限于JavaScript，同样适用于其他语言的性能优化。为其他语言提供的优化建议可能与JavaScript有差别，因为还要考虑到越来越多的JavaScript引擎以及它们各自的奇技淫巧，但所有的技术都基于现代计算机科学知识。

### 第五章 [字符串和正则表达式](./StringsAndRegularExpressions/README.md)

> 在 JavaScript 中，正则表达式是必不可少的东西，它的重要性远超过琐碎的字符串处理。本章使用相当篇幅帮助您了解正则表达式引擎处理字符串的原理，并讲授如何利用这些知识书写正则表达式。

### 第六章 [响应接口](./ResponsiveInterfaces/README.md)

> 大多数浏览器有一个单独的处理进程，它由两个任务所共享:`JavaScript任务`和`用户界面更新任务`。每个时刻只有其中的一个操作得以执行，也就是说当 JavaScript 代码运行时用户界面不能对输入产生反应，反之亦然。或者说，当 JavaScript 运行时，用户界面就被“锁定” 了。管理好 JavaScript 运行时间对网页应用的性能很重要。

### 第七章 [Ajax](./Ajax/README.md)

> Ajax 是高性能 JavaScript 的基础。它可以通过延迟下载体积较大的资源文件来使得页面加载速度更快。它通过异步的方式在客户端和服务端之间传输数据，从而避免页面资源一窝蜂地下载。它甚至可以只用一个 HTTP 请求就获取整个页面的资源。选择适合的传输方式和最有效的数据格式，可以显著改善用户和网站的交互体验。

### 第八章 [Programming Practices](./ProgrammingPractices/README.md)

> 每种编程语言都有其痛点，随着时间的推移，低效模式也不断发展。其原因在于，越来越多的人们开始使 用这种语言，不断扩种它的边界。自 2005 年以来，当术语“Ajax”出现时，网页开发者对 JavaScript 和浏览器的推动作用远超过以往。其结果是出现了一些非常特别的模式，即有精华也有糟粕。这些模式的出现，是因为网络上 JavaScript 的性质决定的。

### 第九章 [Building and Deploying High-Performance JavaScript Applications](./BuildingAndDeploy/README.md)

> 本章的目的是了解如何有效地组织并部署基于 JavaScript 的 Web 应用的一些必要的知识。

### 第十章 [Tools](./Tools/README.md)

> 第九与第十章内容在现代web编程中，有更好的方式。