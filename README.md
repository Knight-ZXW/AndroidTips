
## Activity

## Fragment

## View

## 开发框架

## Java代码层面优化
　　不要滥用嵌套类，这存在隐藏的内存开销，并且在Anroid开发过程中，需要注意可能的内存泄漏。Java实际上不存在嵌套类，java文件被编译成clss文件的过程中，匿名内部类也会生成独立包级的 class 文件，并且如果在嵌套类中引用了外部类的属性或者方法，编译器还会做更多的编译处理，可以[参考](https://realm.io/cn/news/360andev-jake-wharton-java-hidden-costs-android/)

　　能用final修饰的变量就用final修饰，编译器会对此作出优化，具体可以研究 用final 和 不用 final 时class文件的区别


## 开发中遇到的偏门问题

1. **ScrollerView** 设置 **match_parent** 依然无法撑满全屏的问题，可以通过设置 **fillViewport** 为 **true**解决，这样 **ScrollerView** 就不会去计算子View的高度了。