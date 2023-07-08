- [Anki](#anki)
  - [怎么在Anki中用数学公式？](#怎么在anki中用数学公式)
  - [怎么达到注音的效果](#怎么达到注音的效果)
- [Game](#game)
  - [The Legend of Zelda: Tears of the Kingdom](#the-legend-of-zelda-tears-of-the-kingdom)
    - [Yuzu模拟器的按键映射](#yuzu模拟器的按键映射)
- [Playnite](#playnite)
  - [Tips](#tips)
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
- [Proxy](#proxy)
  - [Warp](#warp)

# Anki
## 怎么在Anki中用数学公式？
答案是把Latex语法套进 `\($\)`中，$为Latex语法
## 怎么达到注音的效果
答案是使用`<ruby><rt></rt></ruby>`语法  
例如：<ruby>暗<rt>àn</rt></ruby><ruby>记<rt>jì<rt></ruby>  
排版效果还不太好，需要对每个字单独注音，可能会有一点麻烦  
# Game
## The Legend of Zelda: Tears of the Kingdom
![1](https://static.wikia.nocookie.net/zelda/images/0/0c/%E3%80%8A%E5%A1%9E%E5%B0%94%E8%BE%BE%E4%BC%A0%E8%AF%B4%EF%BC%9A%E7%8E%8B%E5%9B%BD%E4%B9%8B%E6%B3%AA%E3%80%8B%E8%8B%B1%E6%96%87%E6%A0%87%E5%BF%97.png/revision/latest?cb=20220927020617&path-prefix=zh)
### Yuzu模拟器的按键映射
![1](https://imgsa.baidu.com/forum/w%3D580/sign=bbc078c6a151f3dec3b2b96ca4eff0ec/068ef9305c6034a87809088dc51349540823767b.jpg)
# Playnite
链接；https://github.com/JosefNemec/Playnite/  
## Tips
解压汉化Galgame时，要关掉杀毒软件。如果开着杀毒软件（即使是电脑自带的），会删掉某一个文件，导致.exe执行文件打不开。   
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
# Proxy
## Warp
>下载链接：https://1.1.1.1/  
使用方法：
1. 添加Telegram机器人@generatewarpplusbot
2. 向机器人索要密钥
3. 添加密钥