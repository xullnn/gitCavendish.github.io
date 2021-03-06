---
title:  "Backup Mac with timemachine"
categories:
  - Life
tags:
  - timemachine
  - mac
  - tools
  - 备份
layout: post
---

如何使用Mac自带的timemachine进行备份和恢复。

背景说明：

Timemachine是Mac自带的用来备份和恢复系统的工具，其主要特点有：1 选择好备份盘之后会定期备份不用操心设置；2 当备份盘空间占满后会自动删除最旧的备份；3 它能恢复的是所有已经安装的软件和文件。以往在window下的恢复会导致很多原来的软件无法使用，恢复过程中的一些引导操作也不够直白。

![](/images/post_images/dwQnBIkAQga77ZOuG59Z_屏幕快照 2016-12-25 下午2.08.26.png)

---

## 目的：

由于没有相关经验，我阅读了关于Time Machine的官方指南，然后致电apple技术支持，询问具体方法。我想要在借的mac上达到的效果是：

* 1.备份的文件内容能完整迁移。
* 2.我安装过的app不需要再重新装过，像xcode这类巨大的app很费时间。
* 3.由于是借的mac，所以我想要新建一个账户，将所有文件恢复到这个账户下，当我退还mac时，我希望把我的账户下的资料包括这个账户全部抹掉。这是对借你电脑的朋友朋友的基本尊重。
* 4.Safari里的分类网址收藏。这个其实我不担心，我知道这是与apple账户关联的。

---

## 做法：

事实上有两种方法。

一种是登陆账户时会直接自动引导Time Machine进行迁移，前提是这个账户是新建立的。
第二个是登入后使用[迁移助手]进行文件迁移，这个助手不仅可以用来恢复备份，还可以用来从另一台pc上迁移文件到mac（当然系统不同，迁移的文件类型肯定肯定是受限的）。不知道在迁移助手在哪里就直接在spotlight中搜索就出来了。

![](/images/post_images/XqHdzqmhTGCgLCDGicBD_屏幕快照 2016-12-25 下午2.09.04副本.png)

因为我有备份，所以就直接使用第一种方式。

### Step 1 准备

***需要注意的是，你无法用客人账户进行恢复。所以第一步，你需要新建一个管理员账户，这当然需要要到朋友的管理员账号密码。然后你需要先登入原有的一个管理员账户，然后在[系统偏好设置]/[用户与群组]中新建一个管理员账户。***

***另外，如果你的备份是在高版本系统中完成的，而当前mac的操作系统是旧的系统，你需要更新到相同的系统版本。不然系统会提示你由于系统版本差别你无法进行恢复，我在做的过程中就遇到了这个问题。***

### Step 2
当你建立新账户后，然后接入你原先备份备份的硬盘。
接着注销当前账户或者重启以选择登陆你新建立的账户。

### Step 3
当你输完账户密码登陆过程中会自动出现提示，问你是否需要从识别到的备份文件恢复到当前账号，并且会出现一个可选择的列表让你勾选需要恢复的文件。选好之后点击继续，就会开始文件的恢复传输。当然视备份文件大小所用的时间也会不同。

### Step 4
恢复完成后，会提示重启。然后整个恢复过程就完成了。

---

## 结果：

* 1.首先检查了下app的情况，发现自己之前装过的都在。但是和原系统中的app混在了一起，而且发现Time Machine的新备份中也出现了这些多出的app。这只有以后将不要的删除。
* 2.检查了下finder中的文件夹，包括之前做的专案的文件夹，都在。
* 3.Safari中的网址收藏都在，意外的是许多网站都保持着登陆状态，不需要再输一次账号密码。


---
