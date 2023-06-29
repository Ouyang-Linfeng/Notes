- [Anki](#anki)
  - [怎么在Anki中用数学公式？](#怎么在anki中用数学公式)
  - [怎么达到注音的效果](#怎么达到注音的效果)
- [Pot](#pot)
- [Tickeys](#tickeys)
- [WSL](#wsl)
  - [解决报错：\[error 2147942402 (0x80070002) when launching Ubuntu in WSL\]](#解决报错error-2147942402-0x80070002-when-launching-ubuntu-in-wsl)
    - [问题背景](#问题背景)
    - [原因分析](#原因分析)
    - [解决方法](#解决方法)
    - [方法来源](#方法来源)
    - [总结反思](#总结反思)
- [Ehviewer\_CN\_SXJ](#ehviewer_cn_sxj)

# Anki
## 怎么在Anki中用数学公式？
答案是把Latex语法套进 `\($\)`中，$为Latex语法
## 怎么达到注音的效果
答案是使用`<ruby><rt></rt></ruby>`语法  
例如：<ruby>暗<rt>àn</rt></ruby><ruby>记<rt>jì<rt></ruby>  
排版效果还不太好，需要对每个字单独注音，可能会有一点麻烦  
# Pot
链接：https://github.com/pot-app/pot-desktop/  
>使用Pot的目的：换下Utools，因为我使用Utools的目的只有划词翻译和截图OCR
教程网站：https://pot.pylogmon.com/  
# Tickeys
>链接：https://www.yingdev.com/projects/Tickeys/  
作用：键盘打字声模拟软件
# WSL
>这里以wsl2的Ubuntu为标准
## 解决报错：[error 2147942402 (0x80070002) when launching Ubuntu in WSL]
### 问题背景
在wsl中打开Ubuntu报错，报错为：**error 2147942402 (0x80070002)**
### 原因分析
未知，因为很长一段时间我没有修复这个问题，导致我忘记了在出现这个报错之前我做了什么  
可能的报错：安装Python的某一个包时出现的问题，理由参考[方法来源]  
### 解决方法
在环境变量的用户变量中加入"C:\Users\用户名\AppData\Local\Microsoft\WindowsApps"
### 方法来源
https://askubuntu.com/questions/1421805/error-2147942402-0x80070002-when-launching-ubuntu-18-04-in-wsl/  
### 总结反思
1. 及时解决问题，即刻反思问题
2. 在专业论坛寻找答案
3. 寻找更好的python包管理

# Ehviewer_CN_SXJ
链接：https://github.com/xiaojieonly/Ehviewer_CN_SXJ/  
