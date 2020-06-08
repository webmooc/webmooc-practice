# 计算器函数

** 难度 ** :star: 适合初学者

## 练习介绍

如果您是刚开始学习 JavaScript，可以通过本练习综合运用这门语言中的一些基本要点。

实现一个具备简单加减乘除的计算器功能的函数，输入是计算表达式，输出是计算结果。

在这个练习中，我们不需要实现任何界面，我们可以通过 Chrome 自带的开发者工具面板中的控制台，来实现输入输出，从而验证函数实现的正确与否。

## 用例描述

- 表达式为字符串类型，需要把字符串解析为可以计算的数据结构，如树
- 支持多个数字的加减乘除运算表达式，如 3 + 5，10 * 2，6 / 2 + 1，125 - 25 + 6 * 3
- 支持表达式中使用括号来改变运算的优先级，如 5 * (1 + 3)
- 对于表达式中的空格符号可以进行过滤
- 当表达式出现错误表达，比如除数出现 0 时，返回表达式错误的信息

## 练习要求

- 不实现界面

## 练习参考资料

- [Expression Tree](https://www.geeksforgeeks.org/expression-tree/)
- [Tree Traversal](https://www.cs.sfu.ca/~ggbaker/zju/math/traversal.html)
- [MDN JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)