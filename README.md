
## Activity

## Fragment

## View

## 开发框架

## Java代码层面优化
　　不要滥用嵌套类，这存在隐藏的内存开销，并且在Anroid开发过程中，需要注意可能的内存泄漏。Java实际上不存在嵌套类，java文件被编译成clss文件的过程中，匿名内部类也会生成独立包级的 class 文件，并且如果在嵌套类中引用了外部类的属性或者方法，编译器还会做更多的编译处理，可以[参考](https://realm.io/cn/news/360andev-jake-wharton-java-hidden-costs-android/)

　　能用final修饰的变量就用final修饰，编译器会对此作出优化，具体可以研究 用final 和 不用 final 时class文件的区别

## 从零开始系列
[markzhai的 2016 从零开始的Android新系列](http://blog.zhaiyifan.cn/2016/03/14/android-new-project-from-0-p1/)
## Android性能优化系列
[胡凯翻译的Android性能优化典范-非常全面](http://hukai.me/)
[Android 启动界面加载优化](https://gold.xitu.io/post/5874bff0128fe1006b443fa0)

## Material Design

## Android 组件的使用 

### SharePreference
1. [不要滥用 SharePreference](https://zhuanlan.zhihu.com/p/22913991) 


## 音视频

[Camera	实时滤镜方法探讨](http://blog.csdn.net/oshunz/article/details/49862273)
#### 相关项目源码

[RMTP滤镜](https://github.com/begeekmyfriend/yasea)

## 高低层架构方面
[AOP思想在Android中的运用](http://fernandocejas.com/2014/08/03/aspect-oriented-programming-in-android/)



## 拓展
1. [Android进程保活方案介绍](https://mp.weixin.qq.com/s?__biz=MzA3NTYzODYzMg==&mid=2653577617&idx=1&sn=623256a2ff94641036a6c9eea17baab8)

## 开发中使用第三方库解决的小问题
1.[Android超大图显示](https://github.com/davemorrissey/subsampling-scale-image-view)

1. **ScrollerView** 设置 **match_parent** 依然无法撑满全屏的问题，可以通过设置 **fillViewport** 为 **true**解决，这样 **ScrollerView** 就不会去计算子View的高度了。

## 进阶需要了解的原理

1 EventBus RxJava Retrofit 的使用及源码分析

## 开发效率
[高效Android开发者的工具库](http://mp.weixin.qq.com/s?__biz=MzA3OTk4ODkwNA==&mid=2449245750&idx=1&sn=e7ed423c4a52aabfa2e7d2684cb85abf&chksm=8ba337f1bcd4bee7797050bc4e1cad33853e5b782ec088e9f189fca14ddf6de7a86a6311b7e3&scene=0#rd)


## 一些小需求推荐的第三方库

## 面试
[阿里实习面试-1](http://www.jianshu.com/p/cf5092fa2694?utm_source=desktop&utm_medium=timeline)

