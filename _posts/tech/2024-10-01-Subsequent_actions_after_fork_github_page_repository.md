---
layout: post
title: "【记录】Fork Github网站仓库后续设置"
date: 2024-10-01 16:26:41 +0800
categories: "技术"
tags: ["记录","Jekyll"]
---

从旧博客git仓库fork之后，还需要在新仓库的`Action`的标签下面的`Deploy Jekyll site to Pages`激活编译网页内容。

不过发现报错了

![pic]({{ site.baseurl }}/images/boke_migration/github_err.png)<br>

网上查了一下，发现还需要在`settings`的标签下的`Pages`下，使能“Github Action”

![pic]({{ site.baseurl }}/images/boke_migration/github_pages.png)<br>

这样就可以了
