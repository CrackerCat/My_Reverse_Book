# 我理想中的反编译书籍

因为是理想，所以永远不可能达成

施工中，看来还要施工好久。。。

https://tommy-3.gitbook.io/my_reverse_book/

# 画饼 --> 项目目录

## 第零章

我滴各种碎碎念

## 第一章

将快速过一遍逆向工程中的反编译技术，为啥要学习反编译器相关知识？人类有什么缺陷？学习反编译器有什么意义？

## 第二章

反编译器发展历史、通用反编译器架构、关键技术概览。反编译整体流程简述。

## 第三章

SSA与反编译器，详细说明反编译整体流程，为什么SSA这么重要。

介绍从二进制（机器码）→ IR → BasicBlock→ CFG的主要流程与关键技术+难题。

## 第四章

数据流分析，通用反编译中端优化技术合集，内容最多的一章

## 第五章

类型系统还原技术（typing）

## 第六章

控制流还原技术（struct）

## 第七章

查漏补缺+现代反编译技术

## 第八章

第八章为案例分析章节，案例分析章节将分析真实世界中的反编译器是如何实现的，他们的架构啥样，有什么缺陷。

## 第九章

案例分析一：jadx反编译器架构、关键技术、案例讲解

## 第十章

案例分析二：IDA反编译器架构、关键技术、案例讲解

以及

案例分析三：Ghidra反编译器架构、关键技术、案例讲解


## 理论补充章节A

对于现代反编译器进一步优化的讨论；

展望（在我的视野中）下一代反编译器的形态；

思考与其它领域例如机器学习结合的反编译形态？其实我也不懂，也就扯扯淡

## 理论补充章节B

从199?年到20??年间，反编译技术发展中，学术界关键论文的阅读笔记。

# 实践章节


## Ghira+Sleigh

使用Ghidra和它的sleigh框架支持任意指令集的反编译+F5能力，可以拿一些vmp来练手。

## IDA+mircocode

在IDA中编写自己的中间语言优化插件，达到去除Ollvm-flat的目标。
