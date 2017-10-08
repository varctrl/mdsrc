---
title: mycli
tags: tools
date: 2017-10-4
---

#### [mycli](http://mycli.net/)是一个 MySQL 命令行工具,具有自动补全和语法高亮等功能,可以使初学者更加容易上手mysql,减少DBA跑路的几率
<!--more-->

---

### 1.如何安装?

#### linux:

```
sudo apt-get install python
pip sudo pip install mycli
```

#### os x:

```
brew update
brew install mycli
```

### 2.特性

*   mycli使用python prompt toolkit编写
*   支持语法高亮
*   当你输入SQL关键字，数据库的表格和列时可自动补全
*   智能补全，会提示文本感应的补全
*   配置文件在第一次启动时，自动创建在~/.myclirc

### 3.具体使用效果
![](http://wordpress-1252569881.cosgz.myqcloud.com/gif/main.gif)