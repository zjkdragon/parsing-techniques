# 1 简介

解析是对一种给定语法构建其线性表达的过程。这一定义如此抽象，就是为了尽可能进行广泛的解释。“线性表达”可能是对一个句子，一个计算机程序，一组编织图案，一连串的地质地层，一首乐曲，礼仪仪式中的一组动作，总之线性序列就是前面的元素会以某种方式限制[^1]下一个元素的表达。有一些语法已经被我们所掌握，而有些语法目前还在研究之中尚未完全确定，而还有一些语法目前仅仅只是有了一个大体的形状而内部完全不了解。

每种语法，一般都有无限的线性表达（“句子”）来构造表达。也就是说一组有限的语法结构，可以用来构造无限的句子。这是语法范式的主要力量，也是语法重要性的主要源泉：它简要的总结了某一个类的无数个对象的结构。

有几个理由可以展示这个被称为解析的构造过程。其中一个原因是，现有的结构能帮助我们更进一步的展示这个对象。比如当我们知道了一句话的某一个部分是这句话所描述的主体的时候，那么我们就更容易理解这一句话或者将这句话翻译出来了。一旦一篇文档的结构被弄明白之后，这篇文档就能很容易的被理解了。

第二个原因是，在某种意义上语法代表了我们对观察到的句子的理解：关于蜜蜂行为的解释，我们给出的解释越好则我们越能理解它们在做什么。

第三个原因是，部分丢失的信息，可以通过解析器，尤其是错误修复解析器（error-repairing parsers）来完善。如果能给出合理的语法，那么就能设计出一个错误修复解析器，来修复古阿卡德人的泥简（clay tablets）。

给定一堆句子，从中找出产生它们的语法结构，这种反向问题被称为文法推断。这个问题比解析技术，人们对其的了解要更少，不过仍然在进行当中。这个问题不在本书范围之内。国际文法推断座谈会（International Colloquiums on Grammatical Inference）的纪要由Springer出版，名为Lecture Notes in Artificial Intelligence。

[^1]: 如果不存在元素之间的限制，序列仍然是有语法的，只不过语法也许十分繁杂并且难以理解。