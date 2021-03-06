---
title: "排版协议"
weight: 2
---
 

## 标题大写

应该避免标题完全大写, 例如 _A Very Fine Heading_, 
应该书写为 _A very fine heading_ .
没有意义的大写字母或者无视拼写协议的标题, 通常会带来误解.
我们更倾向于使用句子首字母大写的 _sentence case_ 的方式.

## 行的长度

在编辑以plain HTML格式编写的文档来源时, 请将行的长度限制在72个字符以内.

部分先进的贡献者, 使用了
[_semantic linefeeds_](//rhodesmill.org/brandon/2012/one-sentence-per-line),
这是一种不以HTML源码换行为基础的技术, 通过这种技术, 
公众看到的内容将会在文章中以“自然断开”的方式进行分割.
换句话说, 句子之间在更符合语义的地方被分割.
不必多虑每个段落的行, 强迫它们都以明确的边距结尾, 
而是可以将换行符添加到语义有断开的任何地方. 
(译者注：具体区别，对比本网页与原始md后，即可了解本段想表达的意思) 

通过git进行协作时, 
这种技术会使提交的差异更显而易见, 
但这不是我们强制贡献者使用的内容.
