+++
title = "go 1.15版发布了"
weight = 7
date = 2023-05-18T17:03:08+08:00
description = ""
isCJKLanguage = true
draft = false
+++

# Go 1.15 is released - go 1.15版发布了

https://go.dev/blog/go1.15

Alex Rakoczy
11 August 2020

Today the Go team is very happy to announce the release of Go 1.15. You can get it from the [download page](https://go.dev/dl).

今天Go团队非常高兴地宣布Go 1.15的发布。你可以从下载页面获得它。

Some of the highlights include:

其中的一些亮点包括：

- [Substantial improvements to the Go linker](https://go.dev/doc/go1.15#linker) 对Go的链接器进行了实质性的改进
- [Improved allocation for small objects at high core counts](https://go.dev/doc/go1.15#runtime) 改进了高核数下小对象的分配方式
- [X.509 CommonName deprecation](https://go.dev/doc/go1.15#commonname) X.509通用名称的废除
- [GOPROXY supports skipping proxies that return errors](https://go.dev/doc/go1.15#go-command) GOPROXY支持跳过返回错误的代理机构
- [New embedded tzdata package](https://go.dev/doc/go1.15#time/tzdata) 新的嵌入式tzdata包
- [A number of Core Library improvements](https://go.dev/doc/go1.15#library) 一些核心库的改进

For the complete list of changes and more information about the improvements above, see the [**Go 1.15 release notes**](https://go.dev/doc/go1.15).

关于完整的变化列表和有关上述改进的更多信息，请参见Go 1.15发布说明。

We want to thank everyone who contributed to this release by writing code, filing bugs, providing feedback, and/or testing the beta and release candidates. Your contributions and diligence helped to ensure that Go 1.15 is as stable as possible. That said, if you notice any problems, please [file an issue](https://go.dev/issue/new).

我们要感谢所有通过编写代码、提交错误、提供反馈和/或测试测试版和候选版而为这个版本做出贡献的人。你的贡献和勤奋有助于确保Go 1.15尽可能的稳定。也就是说，如果你发现任何问题，请提出问题。

We hope you enjoy the new release!

我们希望你喜欢这个新版本