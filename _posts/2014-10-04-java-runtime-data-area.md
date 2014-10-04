---
layout: post
title: java运行时数据区域
---

Java虚拟机在执行java程序的过程中会把所管理的内存区域划分为若干个不同的数据区域

1.程序计数器（Program Counter Register） 
      线程私有

2.Java虚拟机栈（Java Virtual Machine Stacks）
      线程私有，生命周期与线程相同
      平时大家所说的栈，就是指java虚拟机栈中的局部变量表部分。局部变量表存放：基本数据类型，对象引用 等
    
3.本地方法栈（Native Methond Stacks）

4.Java堆（Java Heap）

5.方法区（Method Area）


