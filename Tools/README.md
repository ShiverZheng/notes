## 小结 Summary

当网页或 Web 应用变慢时，分析从网络下载的资源以及分析脚本的运行性能能让你专注于那些最需要优化的地方。
- 使用网络分析工具找出加载脚本和页面中其他资源的瓶颈，这会帮助你决定哪些脚本需要延迟加载，或者需要进一步分析。
- 尽管传统的经验告诉我们要尽量减少 HTTP 请求数，但把脚本尽可能延迟加载可以加快页面渲染速度，给用户带来更好的体验
- 使用性能分析工具找出脚本运行过程中速度慢的地方，检查每个函数所消耗的时间，以及函数被调用的次数，通过调用桟自身提供的一些线索来找出需要集中精力优化的地方。
- 尽管耗费的时间和调用次数通常是数据中最有价值的部分，但仔细观察函数的调用过程，你也许会发现其他优化目标。
这些工具会帮助你深入了解你的代码在那些通常你比较陌生的编程环境下是如何运行的。在开始优化工作之前先使用它们，以确保开发时间用在刀刃上。