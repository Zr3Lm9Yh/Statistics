# Statistics
统计学笔记

We do not walk but run R（233333）
谢谢老师生动形象的课堂

---tu0---

![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu0.PNG)



首先我们先了解统计学的概念
它是设计，描述，推断 提供方法学的基础

---tu1---
![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu1.png)


描述和统计结合在一起是两种最基本的统计分析类型
研究者通常结合这两种方法，试图对各种社会现象进行探究




接下来讲到了数据，也就是我们收集到的样本，亦或者叫做观测值
信息收集几乎是科学领域的核心，他为我们提供了统计学的观测值


---tu2---

![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu2.png)



接下来就参数和统计量
参数是对某一总体特征的数量概括（可以是平均值，中位数）
统计量是对某一样本的特称的数量概括（样本的信息）

！！在实际的研究中，我们感兴趣的实际是参数的取值，而非从某一个特定的样本中获得统计量的取值

简单随机抽样
很多模型都需要样本是从简单随机抽样而来
需要保证被抽中的样本的概率是相等的


---tu3---

![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu3.png)




接下来我们
可以考到描述统计学的三个方法





---tu4---

![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu4.png)







第一个方法就是制表法如图






---tu5----

![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu5.PNG)






接下来的第二个方法就是绘图法






---tu6---

![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu6.png)





---tu7---


![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu7.PNG)






---tu8---


![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu8.PNG)



---tu9---
![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu9.PNG)



描述统计学的第三个方法
定值分析

---tu10---
![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu10.png)





---tu11---
![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu11.PNG)






---tu12---
![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu12.PNG)







---tu13---
![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu13.PNG)




---tu14---
![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu14.PNG)





---tu15---
![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu15.png)









接下来就是看到了R语言
R是允许用户编辑算法并使用其他可编程工具的一种计算机语言

R能做什么
1.进行运算
2.编写函数
3.应用统计方法进行数据分析
4.编写自己的库函数

R的优势



---tu16---
![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu16.PNG)






以及学习了简单的R语言操作，加油ya恺



-------------一个华丽的分割线---------------
接下来就来到了第二天的学习
首先还是接着R语言的学习，把R的一些操作上手了，还行，介绍了很多函数，介绍了一些包以及应用
R语言中的数值分析函数
我们也知道统计分析的第三个就是数值分析
响应的也有对应的函数



接下来降到了概率分布
老师提到了大数课，不知不觉，其实我们的数学课已经学完了，好多多东西也快忘掉诶
提到了基本概率的一些运算

讲完了这些，就提到了离散型和连续性变量的概率分布
开始讲概率分布了，因为变量是不一样的，所以对应每一个变量结果都可以对应一个概率出来

---tu17---
![ad](https://github.com/Zr3Lm9Yh/Statistics/blob/master/img/tu17.PNG)




---tu18---





---tu19---




通过这个例子之后，我们知道了连续分布是什么，现实中的连续分布有超级超级多，泊松分布，U型分布，啦啦啦
其中最最最重要的就是###正态分布###


正态分布因为包含了生活中各个形态的测量，比如身高，体重，都是服从它（高斯分布）
接下来讲到了正态分布的三个特性


---tu20---




---tu21---




---tu22---



以后我们说一个不可能的事件就可以将3σ事件了
这是一个很重要的经验法则，以后讲到置信区间，它就显得超级超级重要了

我们之前学过可以将变量标准化的过程就是减去均值处以标准差，减去均值就是去中心化
，处以标差就是去掉离散程度，如果这个变量符合正态分布，那么去了均值化以后就服从正态分布了


讲完了正态分布，我们能接着讲到了抽样分布就是用样本估计总体的一种推断，也用R语言跑了下施瓦辛格的加州选举

接下来就是统计推断---估计
接着上节讲下去（统计学的精髓就是抽样分布）
我们看我们的样本发现在取值不同的时候出现的概率不同，就拿施瓦的选举来说



---tu20---
抽样分布的重要性在于，它让我们知道，在某种样本量下，统计量与样本参数间的距离会有多远
有了抽样分布给我们带来的信息，就是看统计量奇怪不奇怪了
统计分布绝对是我认为统计学最最核心的概念之一
我们应该随时提醒自己样本是有随机性的，不同的样本会导致不同的对总体的估计



接下来讲到了样本的均值分布，这是用来数值表示样本的集中趋势的一个值
就好像这样，我们不知道实际的均值是多少，比如投n次硬币出现的几次正几次反，他们的均值是多少，我们就模拟抽样出100次
用来统计，通过观察样本均值的离散程度，我们就可以大概估摸出集中趋势在那一，从而预测样本的均值
具体内容如


---tu21---



于是我们不难得到以下东西


---tu22---




是不是3σ就是很远远啦啦啦
接下来就是我们的中心极限定理，用来说服，不只是正态分布，任何分布，当样本数量大的时候，我们都会发现均值总会出现在中心

中心极限定理:对于一个样本量足够大的随机抽样，样本均值X(bar)的抽样分布近似服从一个正态分布

中心极限定理说明了什么
样本均值的抽样分布近似服从正太分布这条性质对于任何形态的总体分布都成立
代码部分https://github.com/Zr3Lm9Yh/R-Matlab/blob/master/%E4%B8%AD%E5%BF%83%E6%9E%81%E9%99%90%E5%AE%9A%E7%90%86%E7%9A%84%E9%AA%8C%E8%AF%81.R


---tu23---


以上内容就是我们的概率论部分
接下来就是我们的统计推断部分，kai BY day2 加油

