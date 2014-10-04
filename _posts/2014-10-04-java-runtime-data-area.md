---
layout: post
title: Java运行时数据区域
---

Java虚拟机在执行java程序的过程中会把所管理的内存区域划分为若干个不同的数据区域：

### 1.程序计数器（Program Counter Register） 
线程私有。它的作用可以看作是当前线程所执行的字节码的行号指示器，线程切换后通过它也能恢复到正确的执行位置。

###2.Java虚拟机栈（Java Virtual Machine Stacks）
线程私有，生命周期与线程相同,平时大家所说的栈，指的是java虚拟机栈中的局部变量表部分。局部变量表存放：基本数据类型，对象引用等。
    
###3.本地方法栈（Native Methond Stacks）
线程私有，为虚拟机使用到的Native方法服务。

###4.Java堆 (Java Heap)
线程共享，对象实例和数组均在堆上分配。

###5.方法区（Method Area）
线程共享，主要用于存储已被虚拟机加载的类信息，常量，静态变量等。




