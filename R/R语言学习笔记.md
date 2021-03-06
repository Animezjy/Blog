# R语言学习笔记

## 一、R语言简介

> R是免费软件！！

`背景`：R是S语言的一种实现，S语言是AT&T贝尔实验室开发的一种用来进行数据探索、统计分析、作图的解释型语言。(S是商业软件)

### 1.1 R语言特点

* （1）有效的数据处理和保存机制
* （2）拥有一整套数组和矩阵的操作运算符
* （3）一系列的数据分析中间工具
* （4）图形统计可以对数据直接进行分析和显示，可用于多种图形设备
* （5）完善、简洁、高效的程序设计语言
* （6）彻底面向对象的统计编程语言
* （7）与其它编程语言、数据库之间有很好的接口
* （8）R语言是自由软件，有丰富的网上资源

### 1.2 R Studio安装

* （1）先安装R：https://www.r-project.org/
* （2）再安装R Studio：https://rstudio.com/products/rstudio/download/#download

## 二、R语言入门

### 2.1 基本指令

赋值符号为`<-`或`=`，但建议用`<-`

```R
x <- 10 # 赋值10给变量x
```

### 2.2 数据类型

> R是一种基于对象（Object）的语言，在R中看到的一切事物都是对象。

对象的4种基本类型：

* 数值型
* 字符型
* 逻辑型
* 复数型

查看对象的数据类型：

```R
class()
```



