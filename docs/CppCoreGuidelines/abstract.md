---
title: 摘要
summary: 
authors:
    - Zhiyuan Chen
date: 2019-08-06 19:39:28
categories: 
    - C++核心指南
    - 摘要
tags:
---

# 摘要

本系列文档是一组良好使用C++的指南。
本系列文档的目标是帮助人们有效率的使用现代C++。
对于“现在C++”而言，我们指的是ISO C++（目前是C++ 17，但几乎所有的建议对C++ 14和C++ 11都适用）。
换句话来说，如果你现在开始写的话，你会期望你的代码五年后是什么样子？十年后呢？

本指南主要关注相对高级的问题，比如接口、资源管理、内存管理以及并发。
这些规则会影响应用程序架构和库设计。
遵循这些规则将导让你写出静态类型安全、没有资源泄漏、并且捕获比当今代码中常见的更多编程逻辑错误的代码。
并且它会跑得很快 -- 你可以承受得起做对的事。

我们不太关心低级问题，例如命名约定和缩进样式。
但是，没有能帮助程序员的话题是超越范畴的。

我们初始的一组规则强调安全性（各种形式）和简单性。
他们可能有些太过严格。
我们不得不引入更多例外情况以更好地满足现实世界的需求。
我们也还需要更多规则。

您会发现一些与您的期望，甚至与你的经验相悖的规则。
如果我们没有建议你以任何方式改变你的编码风格，我们就失败了！
请尝试验证或反驳规则！
特别是，我们真的希望通过测试或更好的例子来支持我们的一些规则。

你会发现一些明显甚至微不足道的规则。
请记住，本指南的一个目的是帮助那些经验不足或来自不同背景或语言的人加快速度。

许多规则都旨在由分析工具支持。
被违反的规则将会由相关规则的引用（或链接）所标注。
在尝试编写代码之前，我们不希望您记住所有规则。
思考这些指南的一种方法是作为人类可读的工具的规范。

这些规则意在逐步被引入代码库。
我们计划为此建立工具，并希望其他人也这样做。

非常欢迎提出改进意见和建议。
随着我们的理解加深，以及语言和可用库集的改进，我们计划修改和扩展此文档。