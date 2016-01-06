# chapter-1 迈入系统调用的大门

这是全书的第一章。这一章是一张船票。我们将一起从这里登船出发，徜徉在计算机世界的海洋里。当你看到这里的时候，也许你只是一个即将结束大一，刚刚进入实验室的小菜鸟；也许你仅仅学完了C语言，对计算机的世界还所知甚少，内心尚且迷茫但对未来充满期待；或者你只是一个对Linux不甚知晓的好奇宝宝，只是很偶然的点开了这篇文字……这都没有关系，计算机的学习充满了乐趣和挑战，但是前行的路上你并不会孤单。即使学习的过程有点困难，但是同行者中永远不乏师长和朋友。就让我们一同携手，一起踏步前行，把自己从一个学生逐渐塑造成一个合格的计算机相关领域的从业者。在未来，我们也终将站在技术的浪潮之巅，一起做时代的弄潮儿，在中国乃至世界的IT发展史上努力留下自己的痕迹。

也许看到这里你有点迫不及待了，有种撸起袖子大干一番的冲动了。但是别着急，让自己的内心沉寂下来。这一章会有很多文字性质的概念要介绍，虽然会有些枯燥，但是为了以后的学习还是得了解一下。层出不穷的术语也许会吓到刚刚接触这个领域的你，但是我希望你能坚持读完，哪怕目前还不甚理解。一知半解的的读完也没关系的，等到读完了这本书再回过头来读读第一章就好。这种反复阅读和理解的做法在计算机知识的学习中很常见。当你把诸多学科反复学习后再相互印证的理解之后，才能融会贯通，形成网状的知识结构。

计算机科学与技术是在处于高速发展中的，扎实的基础知识会让你在未来面对层出不穷的新技术时，能守住自己内心的那一份清明，不会在繁多的技术中眼花缭乱。因为你基础扎实，所以你很容易透过技术的表层看到本质，也能分析出某个技术从何而来，有何承载，去向何方。所以，无论你选择哪一条技术路线，无论你要工作或者读研，我都希望你记得基础知识的重要性。哪怕这本书你只看到了这里，只记住了这句话，那么我花时间写下这篇文字也就值得了。