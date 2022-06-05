# ThreadLocal详解


# 1. 什么是ThreadLocal

ThreadLocal是用来解决线程安全问题。

我们都知道线程安全是多个线程同时操作同一变量产生的问题。这个里面就涉及到两层含义：

1. 同一时间
2. 同一变量

而我们加锁是破坏了统一时间的因素，ThreadLocal则是用空间换时间。
