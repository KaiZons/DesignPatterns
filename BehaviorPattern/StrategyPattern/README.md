# 策略模式 Strategy

## Intro

> 策略模式（Strategy）：它定义了算法家族，分别封装起来，让它们之间可以互相替换，此模式让算法的变化不会影响到使用算法的 `Context`。
>
> 策略模式是一种定义一系列算法的方法，从概念上来看，所有这些算法完全的都是相同的工作，只是实现不同，它可以以相同的方式调用所有的算法，减少了各种算法类与使用类之间的耦合。

## 使用场景

策略模式就是用来封装算法的，但在实践中也可以用它来封装几乎任何类型的规则，只要在分析过程中听到需要在不同时间应用不同的业务规则，就可以考虑使用策略模式处理这种变化的可能性。

## 优点

- 减少了具体的算法和使用算法类之间的耦合
- 策略模式的 Strategy 类层为 `Context` 定义了一系列的可供重用的算法或行为，继承有助于析取这些算法中的公共功能
- 简化了单元测试，因为每个算法都有i自己的类，可以通过自己的接口单独测试

## More

更多设计模式及示例代码 [传送门](https://github.com/WeihanLi/DesignPatterns)