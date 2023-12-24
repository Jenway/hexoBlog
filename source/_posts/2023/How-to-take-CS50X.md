---
title: How to take CS50X
tags:
  - CS50X
abbrlink: f4100da4
top_img: 
cover: 
hidden: false
date: 2023-01-28 20:21:53
catagories: 技术
categories: 闲聊
---
# How to take CS50X

## What you need

- A `GitHub` Account 👉 <https://github.com/join>
- An `edX` Account 👉<https://authn.edx.org/register>
- A Proxy if you're in China ( mainland ) 👉 `GFW`

## Syllabus

`CS50X` 的最新版是 2023，官网是这个

> <https://cs50.harvard.edu/x/2023/>

非常建议在参与课程之前先看一下官网的 syllabus

> [`Syllabus - CS50x 2023 (harvard.edu)`](https://cs50.harvard.edu/x/2023/syllabus/)

## About Submit

如果你想获得一个证书，你需要：

- submit ten problem sets,
- submit nine labs, and
- submit a final project.

所以，在 `Week0` 的 `pset` 和 `Week1` 的 `lab`中，我们进行若干配置

### Week 0

在 [`Scratch - CS50x 2023 (harvard.edu)`](https://cs50.harvard.edu/x/2023/psets/0/scratch/) 的pset 中，你需要分别提交一个表格，以及绑定你的 GitHub 账号和edX账号

### Week 1

在 [`Lab 1: Population Growth - CS50x 2023 (harvard.edu)`](https://cs50.harvard.edu/x/2023/labs/1/)中，你需要配置好课程的 `codespace`，之后的作业，基本都需要在上面来做

### Week9

这一周需要在一个网站上注册账号,用它们的免费 api 来实现一个 `web app`

在国内裸连的话,相当困难,推荐挂梯子

## 心路历程

以下摘自[我的仓库](https://github.com/Jenway/CS50X)

<a href="https://cs50.harvard.edu/x/2023/"><h1 align="center" >Harvard CS50X 2023</h1></a>

<p align="center">
  <a href="https://jenway.github.io/custom/homepage/index.html">Week 8</a> |
  <a href="https://github.com/Jenway/sdu_meal">Final Project</a>
</p>

> This is CS50

My problem sets and labs for Harvard CS50x 2023 — Introduction to Computer Science 🥰🥰

<a href="https://certificates.cs50.io/dd93c06f-4dd0-4083-b158-9f8469cb285a.png">
  <img src="./src/Final_Project/CS50x .png" alt="This is my CS50" />
</a>

## [x] Week0 Scratch

~~Scratch，但是我一直还没做~~

( 现在做了的喵 🐱) 我在那些提交的作业里看，找到一首叫 `raining man` 的歌，还挺好听，我做的是模仿 chrome 小恐龙的，不过是用的 Scratch 网站上的素材

## [ x ] Week1 C

- ### Lab 1:population

 计算人口增长，验证输入是否符合要求

- ### hello

    经典的 hello,world! 程序

- ### [mario 🧱](./src/week1/mario_more)

 简单利用 for 循环嵌套的命令行绘画

- ### credit

 判断信用卡的真伪，很有意思，需要进 PayPal 官网看看号码规则

## [ x ] Week2 Arrays

- ### Lab 2:Scrabble

 单词依据字母转化为分数，比较大小的游戏，老实说我上学期没想到把分数存在数组里，莎莎的在那条件判断，后来看了 walkthrough 才恍然大悟

- ### readability

   计算文本适合什么阶段的儿童读的，我记得示例文本里有了不起的盖茨比的第一句，让我想起高中午睡时躺在宿舍床上看书的日子，嘛，我那时读第一句还不认识 vulnerable ...

 > In my younger and more vulnerable years my father gave me some advice that I' ve been turning over in my mind ever since.

- ### substitution

 加密文本，蛮常见题目的似乎

- ### Wordle50

 这个超有意思的，什么命令行带颜色，命令行上进度条，命令行上动画什么的，都是让我很喜欢的东西，但是我对猜单词不大感冒，一直没有猜中过。。
  
## [ x ] Week3 Algorithms
  
- ### Lab 3: Sort

 是哪个笨蛋分不清哪个是哪个排序啊，哦原来是我🐒，这个题目真的需要动点脑筋

- ### plurality

 简单的投票

- ### tideman

 进阶版的更强大的投票，我在看引入的时候，还以为画图只是为了便于理解，结果它真的需要图的知识，判断邻接矩阵的有向图是否有环，天啊，如果只是给我这么一个冷冰冰的话，恐怕我是没有动力做的，但是放到一个情境中...照样还是蛮难的。

## [ x ] Week4 Memory

- ### Lab 4: Volume :musical_note:

- ### Lab 4: smiley :smile:

 两个 lab 都是读写文件，很有意思，比读写文本要有意思的多，当然也更难
 不过我用 win 下编译出的程序似乎处理文件并不成功，在 WSL 上就可以用，

- ### recover

 超~棒的，最后得到了 50 张 staff 们拍的 Harvard 照片，不过清晰度感人，嘛，可能单文件再大的话难度也要十分感人了。

- ### filter

 超~棒的，我也能做滤镜软件了✌(并不），自己来实现四种滤镜，黑白，镜像，模糊，查找边缘，跟随着指导来做，真的是让人既有挑战感与焦虑，又有跌宕的惊喜与满足收获，让人欲罢不能，做到深夜————

 > 然后发现 check50 过不了于是又继续改，😭😭😭

## [ x ] Week5 Data Structures

- ### Lab 5: Inheritance

  DNA 遗传什么的，主要是在作业提供的框架下写，要是让我从零写估计能要了我的命，因为我手搓链表都要 debug 老半天 😓

- ### speller

   检验拼写正确与否，一个小工程，如果不用 CS50 codespace 里面自带的 makefile 的话，那就一定要知道编译器基本用法，印象深刻的当然是实现 hashmap ，因为从 26 个字母 到 26 * 26 的组合速度快了不少，我于是又试了试单词前三个字母....
    不出意外的 空间炸了呜呜，让我不禁感叹，那些官方的求prime函数、sort函数都好厉害，staff 的速度到底为什么比我的快呢，大概就是在 hashmap的实现上吧

## [ x ] Week6 Python

- ## Lab 6: World Cup :soccer:

   预测世界杯，很有意思，不过我不看球，所以我看不大懂
  
- ## hello mario credit readability

    属于复习系列，基本照着之前的 C 程序改一改就行，对比让人不禁感慨那句，~~PHP 是世界上~~ 人生苦短，我用 python
  
- ## DNA

 判断 dna 序列是谁的，依旧是按照 TODO 指示来做

## [ x ] Week7 SQL

- ### Lab 7: Song

- ### movies

 熟悉 SQL 语言用的，蛮基础，cs50 的 codespace 配置的很方便

- ### fiftyville 🦆

    `CS50 小黄鸭🦆被偷走了，这究竟是人性的扭曲，还是道德的沦丧？bakery 究竟有何人进入，目击者的证词有何线索？谁在何时停的车，在 ATM 机取款，又是谁订的机票？...`

    我直接吹爆好吗，这个真的只能给一个形容词——帅气，十分帅气的题，让人做下去就没有停止的欲望，似乎真的是在破案一样，因为太有趣我整个晚餐时间都在做，最后破案之后真是有庖丁解牛里说的感觉，

    > “提刀而立，为之四顾，为之踌躇满志”

    做完后，我去楼下买了桶泡面，然后边吃边看 check50 通过，很快乐。
  
## [ x ] Week8 HTML, CSS, JavaScript

- ### Lab 8: Trivia

    按照指导来做即可，cs50 的 codespace 配置的很方便

- ### Homepage

 写一个个人主页，怎么说呢，这种没有标准的东西反而让我很头疼，做了一两天，边看 MDN、W3school、bootstrap 文档什么的
 想实现一个轮播，然后发现大小不对，改了大小又不动了，如此反复，大概...
 不过做完之后，从一开始有点抵触，还是感觉收获良多，有一种疲惫的满足感。
 前端真是博大精深啊...

## [ x ] Week9 Flask

- ### Lab 9: Birthdays 🎂

 按照指导做即可，我居然在做网页应用唉~ codespace 配置好了 flask 很方便

- ### Finance :money_mouth_face:

 这是最后一个作业了，可以说是将 python、SQL 、网页三剑客，Flask 框架综合应用将这四周的内容做了一次总结，很有挑战性，网页前端的话，基本上 copy staff的示例即可，写后端 app.py 配合 SQL 数据库确实让人一开始摸不着头脑，但根据示例来做也，额，😭很有挑战性，至少对我而言。
 最后让我很不明白的是那个 bought 横幅是怎么做的，本来打算手动传参数，仔细看了看网页代码中的 jinja 语法中的 `get_flashed_messages()`才明白这里是要用 flask的 flash 函数。

## [ x ] Final Project

 ~~还没有想法，要不把那个🕊了的 Chrome 小恐龙重新捡起来？还是做个网页应用呢。~~

 (现在完成了喵🐱)

 最终上交的是一个用 Flutter 做的,决定今天吃什么的 APP, [sdu_meal](https://github.com/Jenway/sdu_meal)

 其实这个程序一开始是没打算当作 Final Project 的, 但是 ta 完美的契合了我对着门课的感受

 > All that we ask is that you build something of interest to you, that you solve an actual problem, that you impact your community, or that you change the world. Strive to create something that outlives this course.

 这个 APP 虽然简陋的像毛胚房，但毫无疑问是我用来解决我生活中遇到的问题的，毫无疑问是我想做的，所以 ta 无疑是最有资格作为 Final Project 的，and this was CS50

## 关于 CS50 库的碎碎念

week1 的 hello 是 经典的 hello,world! 程序，让我很惊讶的是这门课居然特意造了个 training wheel (David 语)，很巧妙的规避了 scanf，试问哪个初学 C 语言的同学，没有因为忘掉 & 符号而程序报错呢，实际上课程引入 scanf 在一个很巧妙的地方，大概是讲函数传参的时候，这个时候再讲 scanf ，不仅易于理解为什么要传入变量的地址，而且也让难度变得循序渐进。

然而，我大一上的时候倒腾了半天 CS50 的库也没有用成功... 因为国内的网络环境连不上 cs50 的 codespace，实际上如果能用 codespace 的话，里面的一切都已经配好了，从 编译器到 makefile、再到 sqlite、py解释器、flask...当然就也还有 CS50 的库。

等我大一下的时候，也就是现在，当我能够很轻松的用这个 库的时候，我已经不需要这个辅助轮了😂。

不知道会不会有人看到，如果在本地配置 CS50 的 C 语言库的话，[官方](https://github.com/cs50/libcs50) 的库似乎是给 Linux 和 mac 系统的，所以用 win 的话，对于新生来说并不友好，如果要用的话就是，下载 cs50.c 和 cs50.h，然后包含 在程序里包含 头文件，编译的时候 连接上 cs50.c ，类似于 `clang hello.c cs50.c -o hello` 这样。

嘛，现在看来很简单，当时的我作为一个新手却完全搞不懂，如果能连上 codespace 的话，就会好很多了吧。

欸你别说，我几周前又想起来这个，于是，这一次我开始写 pset 了。

lecture 已经很不错了，pset 也同样让人惊喜，以及 walking through 和种种，让我才发现，我上学期的时候只学习了 CS50X 这门课程的一点点。
