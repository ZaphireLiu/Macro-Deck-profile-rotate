# Macro-Deck-profile-rotate

> A janky python script to rotate Macro Deck's existing profile

[TOC]

## ZH/中文

因为Macro Deck在手机/平板上使用时，若屏幕发生旋转，则会将整个界面转过去，导致大量空间浪费，所以整了个Python程序来生成一个和已有的预设相同但是将布局旋转90度的新预设

### 需求

Windows 10 及以上（Win 8 之类的系统存放数据库的位置不一定一样，不保证能用）
Python 3

### 使用方法

直接下载py文件，打开运行即可
若提示Path Error，则需要自己找到Macro Deck存储`profiles.db`的位置并修改sqlPath的值。
