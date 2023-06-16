- [01 Dart介绍，搭建Dart环境，开发工具介绍，以及运行Dart](#01-dart介绍搭建dart环境开发工具介绍以及运行dart)
  - [Dart中文官网](#dart中文官网)
  - [Dart-sdk下载](#dart-sdk下载)
  - [在VSCode配置开发环境](#在vscode配置开发环境)
  - [怎么写Dart程序](#怎么写dart程序)
  - [⭐解决运行dart代码在VScode中乱码的问题](#解决运行dart代码在vscode中乱码的问题)
- [Dart入口方法介绍 Dart打印 Dart注释 Dart变量 变量申明 变量命名规则](#dart入口方法介绍-dart打印-dart注释-dart变量-变量申明-变量命名规则)
  - [两种Dart入口方法](#两种dart入口方法)
## 01 Dart介绍，搭建Dart环境，开发工具介绍，以及运行Dart
### Dart中文官网
https://dart.cn/  
### Dart-sdk下载

链接：<https://dart.cn/get-dart/archive/>  
下载后解压安装包，并将"D:\program\dart-sdk\dart-sdk\bin"写入环境变量  
在Cmd中输入`dart --version`后能够有反应，证明安装dart成功  

### 在VSCode配置开发环境

1. 在VSCode插件中搜索Dart并安装  
2. 在VSCode中搜索Code Runner并安装  

### 怎么写Dart程序

1. Dart程序的后缀名为`.dart`  
2. 第一个dart程序：

```dart
main(){
  print("hello, world");
}
```
### ⭐解决运行dart代码在VScode中乱码的问题
教程链接：https://blog.csdn.net/weixin_44601948/article/details/105620588/  https://blog.csdn.net/u010351267/article/details/87865318  
在设置中的code-runner.executorMap中点开settings.json  
添加`"code-runner.runInTerminal": true,`  （注意添加的位置，应该添加在一级的{}里面才能成功）  
## Dart入口方法介绍 Dart打印 Dart注释 Dart变量 变量申明 变量命名规则
### 两种Dart入口方法


