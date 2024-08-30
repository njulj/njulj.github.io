---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: false
---


{% if author.dblp %}
You can also find my articles on <a href="{{author.dblp}}">my DBLP page</a>.
{% endif %}


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

### 计算机系统基础（2024秋季学期）
大家在数字电路里都实现过“状态机”，例如一个计数器内部存储了数字 $x$
，每次按下开关执行 $x\leftarrow (x + 1) $ mod $3$
。计算机系统基础这门课 (以及实验部分) 最重要的 take-away message，就是告诉大家日常使用的计算机本质上也是这么一个状态机。在实验课中，我们会用代码严谨地带大家理解这样的 “状态机” 的状态定义、状态转换，以及与外界的交互方式。

实验课首先承担了大家对 “系统编程” 能力的训练，大家会熟悉 Linux 命令行工具的使用，在将命令行工具变成大家日常生活一部分的同时，完成一系列的编程实验。

理解一个系统的最佳实践就是去实现它。因此在本课程的PA 部分，你将会在框架代码的基础上实现一个 RISC-V 全系统模拟器 NEMU，它不仅能运行各类测试程序，甚至还可以运行操作系统和 “仙剑奇侠传”。模拟过硬件的执行，自然就能深 (痛) 入 (苦) 理解计算机系统了。

* 计算机学院：周四 5-6节 1-17周 仙Ⅱ-110
* 匡亚明学院：周五 5-6节 1-17周 仙Ⅰ-201
* 人工智能学院：周五 3-4节 1-17周 逸A-117
* 荣誉顾问：蒋炎岩<jyy@nju.edu.cn> 余子濠<yuzihao@ict.ac.cn>(PA作者)

### 课程资料
1.The Missing Course of Your CS Education （TBA）

### PA大作业
* [PA0: 环境安装与配置](PA/pa0.md)

### Lab小作业
