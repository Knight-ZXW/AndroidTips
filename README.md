

## Java代码层面优化
**不要滥用嵌套类，这存在隐藏的内存开销，并且在Anroid开发过程中，需要注意不要造成内存泄漏。Java实际上不存在嵌套类，java文件被编译成clss文件的过程中，匿名内部类也会生成独立包级的 class 文件，并且如果在嵌套类中引用了外部类的属性或者方法，编译器还会做更多的编译处理，可以[参考](https://realm.io/cn/news/360andev-jake-wharton-java-hidden-costs-android/)*

**在局部作用域，能用final修饰的变量就用final修饰，可以提高性能，具体可以研究 用final 和 不用 final 时,class文件的区别**