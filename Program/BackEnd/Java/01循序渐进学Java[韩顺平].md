[循序渐进学Java](https://www.bilibili.com/video/BV1fh411y7R8/)  
课程地址：https://www.bilibili.com/video/BV1fh411y7R8
- [第 01 章 | Java概述](#第-01-章--java概述)
	- [1-1 | Java简介](#1-1--java简介)
		- [Java的就业方向](#java的就业方向)
		- [Java的体系技术平台](#java的体系技术平台)
		- [Java的重要特点](#java的重要特点)
	- [1-2 | Java的相关术语](#1-2--java的相关术语)
		- [Java虚拟机（JVM）](#java虚拟机jvm)
		- [Java开发工具包（JDK）](#java开发工具包jdk)
		- [JDK, JRM和JVM的关系](#jdk-jrm和jvm的关系)
	- [1-3 | 第一个Java程序和注意事项](#1-3--第一个java程序和注意事项)
		- [第一个Java程序：`HelloWorld.java`](#第一个java程序helloworldjava)
		- [Java程序开发注意事项](#java程序开发注意事项)
		- [Java开发事项和细节说明](#java开发事项和细节说明)
		- [初学Java易犯错误](#初学java易犯错误)
	- [1-4 | Java的注释和规范](#1-4--java的注释和规范)
		- [Java的注释](#java的注释)
		- [Java文档注释](#java文档注释)
		- [Java代码规范](#java代码规范)
	- [1-5 | Java的运行机制](#1-5--java的运行机制)
		- [Java执行流程分析](#java执行流程分析)
	- [1-6 | 其它](#1-6--其它)
		- [Java转义字符](#java转义字符)
		- [DOS命令](#dos命令)
- [第 02 章 | 变量](#第-02-章--变量)
	- [2-1 | 变量快速入门](#2-1--变量快速入门)
		- [变量的概念](#变量的概念)
		- [变量快速入门：`Var01.java`](#变量快速入门var01java)
		- [变量快速入门：`Var02.java`](#变量快速入门var02java)
		- [变量使用注意事项](#变量使用注意事项)
	- [2-2 | 分辨 `+`](#2-2--分辨-)
		- [不同程序中`+`的使用](#不同程序中的使用)
		- [举例：`Plus.java`](#举例plusjava)
	- [2-3 | Java数据类型](#2-3--java数据类型)
		- [Java的数据类型](#java的数据类型)
	- [2-4 | 自动类型转换和强制类型转换](#2-4--自动类型转换和强制类型转换)
- [第 03 章 | 运算符](#第-03-章--运算符)
- [第 04 章 | 控制结构](#第-04-章--控制结构)
- [第 05 章 | 数组、排序与查找](#第-05-章--数组排序与查找)
- [第 06 章 | 面向对象编程（基础）（1/3）](#第-06-章--面向对象编程基础13)
- [第 07 章 | 面向对象编程（中级）（2/3）](#第-07-章--面向对象编程中级23)
- [第 08 章 | 房屋出租系统](#第-08-章--房屋出租系统)
- [第 09 章 | 面向对象编程（高级）（3/3）](#第-09-章--面向对象编程高级33)
- [第 10 章 | 枚举与注解](#第-10-章--枚举与注解)
- [第 11 章 | 异常](#第-11-章--异常)
- [第 12 章 | 常用类](#第-12-章--常用类)
- [第 13 章 | 集合](#第-13-章--集合)
- [第 14 章 | 泛型](#第-14-章--泛型)
- [第 15 章 | 坦克大战（1/3）](#第-15-章--坦克大战13)
- [第 16 章 | 多线程编程](#第-16-章--多线程编程)
- [第 17 章 | 坦克大战（2/3）](#第-17-章--坦克大战23)
- [第 18 章 | IO流](#第-18-章--io流)
- [第 19 章 | 坦克大战（3/3）](#第-19-章--坦克大战33)
- [第 20 章 | 网络编程](#第-20-章--网络编程)
- [第 21 章 | 多用户即时通信系统](#第-21-章--多用户即时通信系统)
- [第 22 章 | 反射](#第-22-章--反射)
- [第 23 章 | 零基础学MySQL](#第-23-章--零基础学mysql)
	- [MySQL安装和配置](#mysql安装和配置)
		- [MySQL安装配置](#mysql安装配置)
- [第 24 章 | JDBC和数据库连接池](#第-24-章--jdbc和数据库连接池)
- [第 25 章 | 满汉楼](#第-25-章--满汉楼)
- [第 26 章 | 正则表达式](#第-26-章--正则表达式)
- [第 27 章 | 算法优化体验课-骑士周游问题](#第-27-章--算法优化体验课-骑士周游问题)


# 第 01 章 | Java概述
## 1-1 | Java简介
### Java的就业方向
JavaEE软件工程师、大数据软件工程师、大数据应用工程师、大数据算法工程师、大数据分析与挖掘、Android软件工程师。
### Java的体系技术平台
- Java SE(Java Standard Edition)标准版
	- 支持面向桌面级应用（如Windows下的应用程序）的Java平台，提供了完整的Java核心API,此版本以前称为J2SE。
- Java EE(Java Enterprise Edition)企业版
	- 是为开发企业环境下的应用程序提供的一套解决方案。该技术体系中包含的技术如：Servlet、Jsp等，主要针对于Web应用程序开发。版本以前称为J2EE
- Java ME(Java Micro Edition)小型版
	- 支持Java程序运行在移动终端（手机、PDA)上的平台，对Java API有所精简，并加入了针对移动终端的支持，此版本以前称为J2ME  
### Java的重要特点
- Java重要特点
	1. Java语言是面向对象的（oop）
	2. Java语言是健壮的。Java的强类型机制、异常处理、垃圾的自动收集等是Java健壮性的根本保证
	3. Java语言是跨平台的
	4. Java语言是解释型的
## 1-2 | Java的相关术语
### Java虚拟机（JVM）
- JAVA虚拟机（Java Virtual machine）
	1. JVM是一个虚拟的计算机，具有指令集并使用不同的存储区域。负责执行指令，管理数据、内存、寄存器，包含在JDK中。
	2. 对于不同的平台，有不同的虚拟机。
	3. JAVA虚拟机机制屏蔽了底层运行平台的差别，实现了”一次编译，到处运行“。
### Java开发工具包（JDK）
- JDK（Java Development Kit）
  - JDK = JRE + Java开发工具
  -  JDK是提供给Java开发人员使用的，其中包含了java的开发工具，也包括了JRE。所以安装了JDK,就不用在单独安装JRE了。
- JRE （Java Runtime Environment）= Java运行环境
	- JRE = JVM + Java的核心类库
	- 包括Java虚拟机（JVM Java Virtual Machine）和Java程序所需的核心类库等，如果想要运行一个开发好的Java程序，计算机中只需要安装JRE即可。
### JDK, JRM和JVM的关系
-  JDK ， JRE 和 JVM 的包含关系 
	1.  JDK = JRE + 开发工具集（例如 Javac ， Java 编译工具等）。
	2.  JRE = JVM + JavaSE 标准类库（ Java 核心类库）。
	3.  JDK = JVM + Java 标准类库 + 开发工具集。
	4.  如果只想运行 .class 文件，只需要 JRE 。
## 1-3 | 第一个Java程序和注意事项
### 第一个Java程序：`HelloWorld.java`
```java
//HelloWorld.java
//这是Java快速入门，演示Java的开发步骤
//对代码的相关说明
//1. public class Hello 表示 Hello 是一个类，是一个 public 的类
//2. Hello { } 表示一个类的开始和结束
//3. public static void main(String[] args) 表示一个主方法，即我们程序的入口
//4. main() { } 表示方法的开始和结束 
//5. system.out.println("hello,world~"); 表示输出 "hello,world~" 到屏幕
//6. ; 表示语句结束
public class HelloWorld {

	//编写一个main方法
	public static void main(String[] args) {
		system.out.println("hello,world~");
	}
}
```
### Java程序开发注意事项
>**对修改后的 `.java` 源文件需要重新编译，生成新的`.class`文件后，再进行执行，才能生效。**
### Java开发事项和细节说明
1. Java 源文件以 `.java` 为拓展名。源文件的基本组成是类（class），如本类中的 Hello 类
2. Java 应用程序的执行入口是 `main()` 方法。它有固定的书写格式： `public static void main(String[] args { }` 。
3. Java 语言严格区分大小写
4. Java 方法由一条条语句构成，每个语句以 `;` 结束。
5. 大括号都是成对出现的，缺一不可。（习惯，先写 `{ }` 再写代码）
6. 一个源文件中最多只能有一个 `public` 类。其它类的个数不限。（编译后，每一个类，都对应一个 `.class` )
7. 如果源文件包含一个 public 类，则文件名必须按该类名命名。
8. 一个源文件中最多只能有一个 `public` 类。其它类的个数不限，也可以将 `main` 方法写在非 `public` 类中，然后指定运行非 `public` 类，这样入口方法就是非 `public` 的 `main` 方法。
### 初学Java易犯错误
1. 找不到文件
2. 主类名和文件名不一致
3. 缺少分号
## 1-4 | Java的注释和规范
### Java的注释
1. 单行注释
```java
//单行注释
```
1. 多行注释
```java
/*
多行注释
*/
```
### Java文档注释
```java
//Comment02.java
/**
 * @author Olive
 * @version 1.0 
 * 
 */
public class Comment02{

	public static void main(String[] args){
		System.out.println("hello,world");
	}
}
```
### Java代码规范
1. 类、方法的注释，要以 javadoc 的方式来写。JavaDoc的注释，往往是给代码的维护者看的，着重告述读者为什么这样写，如何修改，注意什么问题等。
2. 使用 <kbd>tab</kbd> 操作，实现缩进，默认整体向右边移动，时候用shift+tab整体向左移。
3. 运算符和 = 两边习惯性各加一个空格。
4. 源文件使用 utf-8 编码。
5. 行宽度不要超过 80 字符。
6. 代码编写次行风格和行尾风格。
## 1-5 | Java的运行机制
### Java执行流程分析
![Java执行流程分析](https://cdn.jsdelivr.net/gh/51flow/Picture/img/202302222108643.png)
## 1-6 | 其它
### Java转义字符
```java
//ChangeChar.java
//演示转义字符的使用
public  class ChangeChar {
	//编写一个 main 方法
	public static void main(String[] args) {
		System.out.println("北京\t天津\t上海");  //\t 一个制表位，实现对其的功能
		System.out.println("Jack\nSmith\nMary");//\n 换行符
		System.out.println("C:\\Windows\\System32\\cmd.exe");//		\\ 一个\、\\
		System.out.println("C:\\\\Windows\\\\System32\\\\cmd.exe");
		System.out.println("老韩说：\"要好好学习Java，有前途\"");//		\' 一个'
		System.out.println("老韩说：\'要好好学习Java，有前途\'");//		\' 一个'
		System.out.println("韩顺平教育\r北京"); //北京平教育//\r 一个回车
		System.out.println("韩顺平教育\r\n北京");  //韩顺平教育 北京	
	}
}
```
### DOS命令
- 常用的 DOS 命令
	1. `dir` 查看当前目录有什么内容
	2. `cd` 切换到其他盘下
	3. `cd ..` 切换到上一级
	4. `cd \` 切换到根目录
	5. `tree` 查看指定的目录下所有的子级目录
	6. `cls` 清屏
	7. `exit` 推出DOS
# 第 02 章 | 变量
## 2-1 | 变量快速入门
### 变量的概念
>**变量相当于内存中一个数据存储空间的表示,你可以把变量看作是一个房间的门牌号,通过门牌号我们可以找到房间，而透过变量名可以访问到变量**
###  变量快速入门：`Var01.java`
```java
//Var01.java
public class Var01 {
	//编写一个 main 方法
	public static void main (String [] args) {
		//声明变量
		int a;
		a = 100 ;
		System.out.println(a);
		//还可以这样用
		int b = 800;
		System.out.println(b);
	}
}
```
### 变量快速入门：`Var02.java`
```java
//变量快速入门
public class Var02 {
	public static void main (String []args){
		//记录人的信息
		int age = 39;
		double score = 88.9;
		char gender = '男';
		String name = "Olive";
		//输出信息
		System.out.println("人的信息如下");
		System.out.println(name);
		System.out.println(age);
		System.out.println(score);
		System.out.println(gender);
	}
} 
```
### 变量使用注意事项
1. 变量表示内存中的一个存储区域（不同的变量，类型不同，占用的空间大小不同，比如：int 四个字节，double就是八个字节）
2. 该区域有自己的名称（变量名）和类型（数据类型）
3. 变量必须先声明，后使用，即有顺序
4. 该区域的数据可以在同一类型范围内不断变化
5. 变量在同一作用域内不能重名
6. 变量 = 变量名 + 值 + 数据类型（这是变量的三要素）
## 2-2 | 分辨 `+` 
### 不同程序中`+`的使用
1. 当左右两边都是数值型时，则做加法运算
2. 当左右两边一方为字符串，则做拼接运算
3. 运算的顺序是从左到右
### 举例：`Plus.java`
```java
//Plus.java
public class Plus{
	//编写一个main方法
	public static void main(String[] args){
		System.out.println(100 + 98);//198
		System.out.println("100" + 98);//10098
		System.out.println(100 + 3 + "hello");//103hello
		System.out.println("hello"+100 +3);//hello1003
	}
}
```
## 2-3 | Java数据类型
### Java的数据类型

## 2-4 | 自动类型转换和强制类型转换
# 第 03 章 | 运算符
# 第 04 章 | 控制结构
# 第 05 章 | 数组、排序与查找
# 第 06 章 | 面向对象编程（基础）（1/3）
# 第 07 章 | 面向对象编程（中级）（2/3）
# 第 08 章 | 房屋出租系统
# 第 09 章 | 面向对象编程（高级）（3/3）
# 第 10 章 | 枚举与注解
# 第 11 章 | 异常
# 第 12 章 | 常用类
# 第 13 章 | 集合
# 第 14 章 | 泛型
# 第 15 章 | 坦克大战（1/3）
# 第 16 章 | 多线程编程
# 第 17 章 | 坦克大战（2/3）
# 第 18 章 | IO流
# 第 19 章 | 坦克大战（3/3）
# 第 20 章 | 网络编程
# 第 21 章 | 多用户即时通信系统
# 第 22 章 | 反射
# 第 23 章 | 零基础学MySQL
## MySQL安装和配置
<!-- ## 数据库
### 创建
### 查看、删除数据库
### 备份恢复数据库
## 表
## MySQL数据类型
## CRUD
## 函数
## 内连接
## 外连接
## 约束
## 索引
## 事务 -->
### MySQL安装配置

# 第 24 章 | JDBC和数据库连接池
# 第 25 章 | 满汉楼
# 第 26 章 | 正则表达式
# 第 27 章 | 算法优化体验课-骑士周游问题
