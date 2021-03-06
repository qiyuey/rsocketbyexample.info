+++
title = "关于本站"
+++

很多同学在第一次接触RSocket的时候都会有这样的疑问，RSocket能做什么？ [https://rsocket.io](https://rsocket.io) 网站看起来好像空白一片，全部是文本，好像没法解释我心中的疑问。在给出RSocket Tags云图后，好像RSocket什么都能做。如果什么都能做，但是没有实际的设计案例，那么就等于什么都没有做啊。

![RSocket Tags Cloud](/images/rsocket_tags.png)

这个就是RSocket By Example站点的由来，将基于RSocket常用的案例、设计方法、设计模式等进行整理，方便大家参考。当然我们不可能罗列出所有的适用场景，如果你有更好地基于RSocket的设计想法，也欢迎反馈，我们也会添加到该站点上。

本站大多数的案例出发点都来自下面五个主要考虑因素：

* Convenience: 便捷性。不要那么复杂、晦涩，让每一个开发者都能明白且使用简单。复杂的架构设计、运维的高要求、专家级指导等，这些都不是我们的出发点。
* Speed: 速度。开发速度、运行速度等，都是要考量的因素，我们相信Reactive和FP结合会让开发更容易，全异步化让运行速度更快。
* Security: 安全。现在的架构设计已经不是那个牺牲安全来换取XOXO的时代啦，安全从一开始就就需要考量。
* Cost: 成本。必须是节约客户成本的，而是一套非常复杂的架构设计，客户需要支付额外的基础设施和设备、人员培养、购买商业产品和支持、咨询服务等等，这些统统都不需要。
* Features: 特性。必须包括丰富的特性，即便现在用不到，但是要能给未来扩展的空间，你的客户/合作方都有用到的潜在可能。

RSocket作为一个通讯协议，提供了各种语言的SDK实现，所以你不用担心多语言接入和互通的问题，你甚至在浏览器或者WebAssembly中直接使用RSocket，这完全没有问题。

![RSocket SDK Stack](/images/site/rsocket-sdk-stack.jpg)

最后，我们将Reactive的生态系统也说明一下，方便大家对整个Reactive生态有一个全面的了解。

![Reactive Ecosystem](/images/reactive-ecosystem.png)

希望本站提供的内容能够帮助你更好地理解RSocket及其分布式架构设计，同时非常欢迎你提出宝贵建议。
