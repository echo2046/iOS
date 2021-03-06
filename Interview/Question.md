[iOS 开发面试问题](https://github.com/lzyy/iOS-Developer-Interview-Questions)部分总结

* 什么是响应链，它是怎么工作的？
<details>
<summary> 参考内容 </summary>

[ResponderChain](https://github.com/luckyvondoit/OC_Document/blob/master/UIKit/ResponderChain/ResponderChain.md)

</details>

* 如何访问并修改一个类的私有属性？

<details>
<summary> 参考内容 </summary>
</br>

**共三种方式:**

- 过KVC来设置
- runtime动态改变
- 过 msg_send() 设置

例子：
[IFXChangePrivateProperty.h](https://github.com/luckyvondoit/OC_Foundation/blob/master/Classes/ChangePrivateProperty/IFXChangePrivateProperty.h)
[IFXChangePrivateProperty.m](https://github.com/luckyvondoit/OC_Foundation/blob/master/Classes/ChangePrivateProperty/IFXChangePrivateProperty.m)

</details>

1. 说一下OC的反射机制；
2. block的实质是什么？有几种block？分别是怎样产生的？
3. __block修饰的变量为什么能在block里面能改变其值？
4. 说一下线程之间的通信。
5. 你们应用的崩溃率是多少？
6. 说一下hash算法。
7. NSDictionary的实现原理是什么？
8. 你们的App是如何处理本地数据安全的（比如用户名的密码）？
9. 遇到过BAD_ACCESS的错误吗？你是怎样调试的？
10. 什么是指针常量和常量指针？
11. 不借用第三个变量，如何交换两个变量的值？要求手动写出交换过程。
12. 若你去设计一个通知中心，你会怎样设计？
13. 如何去设计一个方案去应对后端频繁更改的字段接口？
14. KVO. KVC的实现原理
15. 用递归算法求1到n的和
16. category为什么不能添加属性？
17. 说一下runloop和线程的关系。
18. 说一下autoreleasePool的实现原理。
19. 说一下简单工厂模式，工厂模式以及抽象工厂模式？
20. 如何设计一个网络请求库？
21. 说一下多线程，你平常是怎么用的？
22. 说一下UITableViewCell的卡顿你是怎么优化的？
23. 看过哪些三方库？说一下实现原理以及好在哪里？
24. 说一下HTTP协议以及经常使用的code码的含义。
25. 设计一套缓存策略。
26. 设计一个检测主线和卡顿的方案。
27. 说一下runtime，工作是如何使用的？看过runtime源码吗？
28. 说几个你在工作中使用到的线程安全的例子。
29. 用过哪些锁？哪些锁的性能比较高？
30. 说一下HTTP和HTTPs的请求过程？
31. 说一下TCP和UDP
32. 说一下静态库和动态库之间的区别
33. load和initialize方法分别在什么时候调用的？
34. NSNotificationCenter是在哪个线程发送的通知？
35. 用过swift吗？如果没有，平常有学习吗？
36. 说一下你对架构的理解？
37. 为什么一定要在主线程里面更新UI？

