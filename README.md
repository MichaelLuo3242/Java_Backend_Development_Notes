# Java_Backend_Development_Notes

# Java_Backend_Development_Notes

Java 后端开发所需技术栈的整理，包括《Java基础语法（上）1-10》、《Java基础语法（中）1-14》、《Java基础语法（下）15-18》、《Java基础（上）》、《Java基础（下）》、《Java基础之HashMap底层实现》等等

## 《Java基础语法（上）1-10》

1. 类的概念

   类包括属性和行为

   成员变量和局部变量的区别

   构造函数

2. 继承

   成员变量的特点 

   成员函数的特点 

   构造函数的特点

3. 抽象类

   抽象类的特性和使用 

   抽象类的使用限制 

4. 接口（interface）

5. 抽象类和接口的区别理解

   语法层面的区别

   设计层面的区别

6. 多态

   向上转型 upcasting 

   向下转型 downcasting

   多态的判断

   多态调用成员变量，成员函数，静态函数的特点

7. 内部类

8. 异常

   自定义异常 

   异常捕获 

9. 多线程

   设计线程的原因

   JVM中多线程解析

   线程名称

   多线程的运行栈内存情况

   多线程的状态

   多线程的第一种创建方式 —— 继承 Thread 类

   多线程的第二种创建方式——实现 Runnable 接口

   多线程安全问题产生的原因

   两种同步方法解决安全隐患

   多线程下单例设计模式

   多线程死锁示例

10. 线程间通信

    多线程通信的 —— 等待唤醒机制

    多线程通信的 —— 多生产者多消费者“多生产多消费”问题

    多线程中 wait 和 sleep 方法

    线程停止的方式

    多线程的其它方法



## 《Java基础语法（中）1-14》

11. String 类

12. StringBuffer 类

13.  基本数据类型对象类型

14. 集合

    1⃣️集合概念和特点

    2⃣️集合框架

    3⃣️Collection 的常见方法

    4⃣️迭代器

    5⃣️Collection 的子类接口 List

    6⃣️Collection 的子类接口 Set 中的 HashSet

    7⃣️Collection 的子类接口 Set 中的 TreeSet

    8⃣️集合 Collection 的总结

    9⃣️泛型 ⭐️

    🔟Map 集合 ⭐️

    1⃣️1⃣️ 集合工具类 Collections

    1⃣️2⃣️数组工具类 Arrays

    1⃣️3⃣️JDK 1.5 特性



## 《Java基础语法（下）15-18》

15.  `IO` 流

    1⃣️概念

    2⃣️字符流操作

    3⃣️缓冲区 —— BufferedWrite

    4⃣️缓冲区 —— BufferedReader

    5⃣️流操作和缓冲区操作的区别

    6⃣️装饰设计模式

    7⃣️字节流

    8⃣️键盘输入方法

    9⃣️转换流（便于键盘录入）

    🔟`IO` 流的操作规律

    1⃣️1⃣️转换流的编码解码

    1⃣️2⃣️File 类

    1⃣️3⃣️Properties 集合

    1⃣️4⃣️`IO` 包的其它类

    1⃣️5⃣️文件切割与合并

    1⃣️6⃣️对象序列化和反序列化

    1⃣️7⃣️ RandomAccessFile

    1⃣️8⃣️管道流

    1⃣️9⃣️DataInputStream 和 DataOutputStream

    2⃣️0⃣️ByteArrayInputStream 和 ByteArrayOutputStream

    2⃣️1⃣️编码问题

16. 网络编程

    1⃣️OSI参考模型（七层）

    2⃣️TCP/IP 参考模型（四层）

    3⃣️网络三要素

    4⃣️IP对象 —— InetAddress

    5⃣️域名解析

    6⃣️UDP

    7⃣️TCP —— 客户端

    8⃣️TCP —— 服务端

    9⃣️关于 TCP 传输的小练习

    1⃣️0⃣️网络架构

17. 反射

18. 正则表达式



## Java基础（上）

1. 8种基本数据类型

2. 自动拆箱和装箱常见面试题

3. Java常见的关键字

   ⭐️ static 关键字的作用是什么

   **引申**：静态属性和静态方法可以被继承吗？

   ⭐️ final 关键字super和this 用法和区别

4. Comparable和Comparator的区别

5. ⭐️ Java中方法的参数传递机制

6. Java的深拷贝和浅拷贝的区别

7. ⭐️ 什么是序列化和反序列化

8. ⭐️ Java中 “`==`” 和 `equals` 的区别

9. 如何判断两个对象相等

   引申：`hashMap`底层是怎么利用`hashcode`的

10.  ⭐️  String和StringBuilder、StringBuffer的区别

11. Object类有哪些方法

12. package的权限

13. 异常体系⭐️

14. Java的IO、NIO、AIO的区别

    BIO (Blocking I/O)

    NIO (New I/O)

    AIO (Asynchronous I/O)



## Java基础（下）

15. ⭐️Java反射机制

    反射的原理

    `Class.forName` 和 `classloader` 的区别（结合 `JVM` 类加载）

    反射的用途

16. ⭐️面向对象的三大特征

    封装

    继承

    多态

17. 简述继承与组合的区别和选择

    继承

    组合

    组合和继承如何选择

18. ⭐️Java中方法重载和重写的区别（多态体现）

    重载（Overloading）

    重写（Override）

19. Java 中静态属性和静态方法

20. ⭐️抽象类和接口的区别

21. ⭐️ `ArrayList` 和 `LinkedList` 的区别

    ArrayList 底层实现

    LinkedList 底层实现

    ArrayList 和 LinkedList 新增元素时究竟谁快

    ArrayList 和 LinkedList 删除元素时究竟谁快

    ArrayList 和 LinkedList 遍历元素时究竟谁快
