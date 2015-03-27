什么是Markdown
==================

Markdown是一个将文本转化为HTML的工具。简单来说，Markdown是一个兼顾可读性与易用性的轻量级标记体系。Markdown并不追求大而全，它只关心HTML里最常用的几个标记，对于一些不常用的标记它允许直接将HTML标记插入文本

标题2
-----------------

Atx方式
# 标题1
## 标题2
###### 标题6

> 这是一个引用，
> 这里木有换行，   
> 在这里换行了。
> > 内部嵌套


* Item 1
* Item 2
* Item 3

+ Item 1
+ Item 2
+ Item 3

- Item 1
- Item 2
- Item 3


1. Item 1
2. Item 2
3. Item 3

这是一个Inline[示例](http://equation85.github.com "可选的title")。
这是一个Reference[示例][ref]。
[ref]: http://equation85.github.com

Inline示例：![替代文本](/assets/images/jian.jpg "可选的title")
Reference示例：![替代文本][pic]
[pic]: /assets/images/ship.jpg "可选的title"
HTML示例：<img src="/assets/images/jian.jpg" alt="替代文本" title="标题文本" width="200" />