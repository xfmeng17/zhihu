# 关于知乎回答与Markdown

2018年最重要的一个工作便是重新编辑自己在知乎上的高赞回答。随着全面github和重视输出的ideal影响下，发现使用Markdown是进行文字编辑必经之路，目前有3个需求：

* Github
* 知乎
* 如何与印象笔记同步

****

### 2018-02-27 配置sublime text 3

1. MarkdownEditing: markdown编辑插件
2. OmniMarkupPreviewer: 浏览器实时浏览插件
3. Monokai Extended: Monokai的markdown主题
 
****

```
配置一个sublime累的我要死，难道我还要回家把剩下的3个电脑上的sublime都配置一遍么？？难道subliem就没有共享配置？？
```

### 2018-02-28 重新编辑知乎回答 [如何学习数据结构？](https://www.zhihu.com/question/21318658/answer/42690576)

### 前言 ###

2016年1月第一次编写这个答案，之后于2015年6月和2018年3月分别进行整体修改。只适合于入门，评论中的重点问题参见集中回复。

****

### 正文 ###

我觉得入门学习算法与数据结构时应包含三个部分：

* 选择一本合适的书。
* 编程实现和应用。
* 重温


#### 1. 选择一本合适的书 ####

十分推荐普林斯顿的这本橙书：[《算法 第四版》](https://algs4.cs.princeton.edu/home/)，是我认为最适合拿来入门的。在橙书中淡化了算法分析和证明，强调了实现和应用，并且通过一些有趣的习题对比显示了优秀的算法与数据结构在时间和空间上的高效。

橙书是使用Java进行代码实现，在第一章前两个小章节介绍了全书可能需要使用到的一些简单的Java语法，使得我们不会将过多的精力花费在编程语言的学习上。

并且普林斯顿在[Coursera](https://www.coursera.org/)上也公开了两门对应课程：[Algorithms, Part I](https://www.coursera.org/learn/algorithms-part1)和[Algorightmsm, Part2](https://www.coursera.org/learn/algorithms-part2)。依次注册待开课后，**认真跟住**课上内容（英文授课有字幕，如果已熟稔书本内容，并事先自己翻译了课件，英文听力不好也能理解。），并**独立完成** *Exercises（选择题）*，*Programming Assignmengs（编程作业）*和*Job Interview Questions（面试题）*。

这2门Coursera公开课在知乎上也盛誉很多，在此不多赘述。不收费，同时也不给电子证书，一年开课几次，可随时加入。关于书后习题的讨论，可以参考：[算法 第四版(algorithms 4th edition ) 这本书有配套的习题答案吗？](https://www.zhihu.com/question/27876056/answer/64157598)。

#### 2. 编程实现和应用 ####

理解一个数据结构和编程实现其完整功能是完全不同的挑战。自己动手亲自实现一些基础数据结构（如排序，集合，图和字符串处理等，然而平衡树们就显得过难了。）的简化版API能够极大的提升对数据结构内部细节的理解。

##### 编写API #####

我曾使用的一个较笨的方法是尝试默写书本中的实现。另一种较有成就感的方法是在如[Leetcode](https://leetcode.com)等OJ([Online Judge](https://baike.baidu.com/item/Online%20Judge/2397914?fr=aladdin))上，选择一些简单的但会使用到上述基础数据结构的题目，自己实现那些需要使用到的数据结构，而不使用语言本身提供的，如c++的STL或Java的util。

##### 可视化帮助 #####

同时，除了底层coding，最好也从顶层宏观的去观察一种数据结构的各种操作。这里推荐一个动态可视化网站[Visualgo](https://visualgo.net/en)。比如进入Binary Heap（二叉堆），插入一个77，就可以看到整个堆的变化过程。可以通过左下角的按钮调慢演示过程。正刚刚在书本上学完二叉堆原理，可能也自己动手code实现了过程，那么再在网站上演示一下元素“初始化”，“增删改查”，“排序”等过程，会带来一些更直观的印象。

![Visualgo: Binary Heap](https://github.com/xfmeng17/zhihu/blob/master/HowToLearnDS/visualgo.png?raw=true)

（在Visualgo上进行二叉堆操作的演示）

##### 学会应用 #####

* 认真且独立完成Coursera上《算法 第四版》的公开课作业。
* 对书本后的编程习题进行实现。
* 在Leetcode等OJ上解决相关数据结构的题目。
* 网上一些开源项目等。

以上这些都是能够较快带来成就感的，算法与数据结构学习不算轻松，能有一些及时的正反馈最好了。

#### 3. 重温 ####

因为算法与数据结构所涵盖的知识较多，所以一本书里的内容可能都需要分几个阶段去学习，难免会遗忘之前的内容。我建议敏捷学习，尽量快的往后学习。如果一个知识点实在不懂，可以存疑，“不求甚解”，很多时候经过后面的学习，前面的一些内容就自然明了。


除了基本的复习，还需要其他书籍进行一些补充和升级。推荐[《算法导论》](https://mitpress.mit.edu/books/introduction-algorithms)，除显著加强算法分析的能力外，如摊还分析，动态规划等章节是对《算法 第四版》较好的补充。其网上开放课程，中文有[网易公开课](http://open.163.com/special/opencourse/algorithms.html)，英文有[Coursera: Algorithms Specialization](https://www.coursera.org/specializations/algorithms)（可不要证书，免费旁听。）。

总之，要多做题多总结（OJ上的编程题，书后思考题，大公司的面试题等等）！


