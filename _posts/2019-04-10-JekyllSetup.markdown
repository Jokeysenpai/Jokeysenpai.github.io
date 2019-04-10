---
layout: post
title:  "Jekyll Setup"
date:   2019-04-10 00:01:22 +0800
categories: Routine
---
# Jekyll真香

围绕github服务建立服务器的方法有jekyll框架和hexo框架，本文希望能通俗易懂地介绍在windows环境下由jekyll框架从零开始建立github静态博客的方法。

使用github+jekyll的方法编写博客的优点有：

1.免费

2.可定义度高

3.运行效率高

缺点有：

1.没有独立域名

2.交互需要用不便利的插件disqus

3.需要前端知识

## 需要的工具有

· [git][1]: 版本管理工具，在本文过程中通过git来和云端交互信息。

· [GitHub][2]: 嘿嘿嘿嘿嘿嘿

· [Jekyll][3]: 我们搭建博客的框架；需要[Ruby][4]支持，下载最新版本ruby环境即可，ruby命令行可以从开始菜单直接打开

· Markdown: 需要一些基础的md知识来编写博客内容

## 总体流程是：
	
创建GitHub账户，创建新库作为网站host，然后由ruby命令行在本地下载生成原生的jekyll网站，经过编辑之后重新上传到GitHub库中，直接上线！

## 创建GitHub账号和库

注册一个GitHub账号并登陆，看右上角加号位置，点击创建新库

![repo](https://github.com/Jokeysenpai/Jokeysenpai.github.io/blob/master/_img/image1.png)

然后记得输入库名的时候要和自己的username一致，虽然没弄清楚为什么，但是大概和框架建立时的连接有关系

![na](https://github.com/Jokeysenpai/Jokeysenpai.github.io/blob/master/_img/image2.png)

按下创建即可，此时在库内会生成一些文件，不过无所谓之后全部都要换掉！

## 使用GitHub desktop把库文件拉下来

下载[GitHub desktop][5] 然后可以看到自己的库文件，fetch下来一个文件夹然后我们在文件夹中进行操作。

![fetch](https://github.com/Jokeysenpai/Jokeysenpai.github.io/blob/master/_img/image3.png)












[1]: https://git-scm.com/
[2]: https://github.com/
[3]: https://jekyllrb.com/
[4]: https://www.ruby-lang.org/en/downloads/
[5]: https://desktop.github.com/
