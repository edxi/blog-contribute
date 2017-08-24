这是给DXC守护者网站投稿用的repository。

建站前只是想把github的gh-pages改善下，然后弄着弄着就索性开始建站了，后来最终选用github page+hexo作建站工具。

## 投稿指南

​    建站前只是想把github的gh-pages改善下，然后弄着弄着就索性开始建站了，后来最终选用github page+hexo作建站工具，站点内容可以使用markdown书写，可以用纯文本编辑器书写或markdown编辑器，然后非常欢迎大家上传到这个[blog-contribute repository](https://github.com/edxi/blog-contribute)，我会定期更新到[DXC守护者](https://edxi.github.io)网站上的。

### 投稿格式

​    投稿接受markdown格式，可以用markdown编辑器来编辑（可以做work/pdf等格式的转换，但是会有部分格式损失，所以最好还是直接用markdown编辑器来书写）。

​    **（可选）**由于采用hexo建站，所以还能接受下面这类格式作为页面头信息，类似于下面格式写在md文件最前面写好就可以了（参数也都是可选的）：

```yaml
---
title: 文章标题
date: 2013/7/13 20:46:25
categories:
- 学习
- git
tags:
- git
- github
- git page
---
```

这里列举了些参数：

| 参数           | 描述        | 默认值    |
| ------------ | --------- | ------ |
| `title`      | 标题        |        |
| `date`       | 建立日期      | 文件建立日期 |
| `updated`    | 更新日期      | 文件更新日期 |
| `comments`   | 开启文章的评论功能 | true   |
| `tags`       | 标签        |        |
| `categories` | 分类        |        |



### 投稿方式

​    目前推荐下面集中方式上传.md文件：

- 最简单的方式是直接通过github的issues——可以直接在[DXC守护者](https://github.com/edxi/edxi.github.io/issues)和[blog-contribute](https://github.com/edxi/blog-contribute/issues)这两个repo里写issue，然后把.md的内容黏贴上来，并注明这是篇需要投稿的文章，我看过后会把相应内容post到网站的。
- 如果想要以文件形式维护自己的文章列表，可以先fork [blog-contribute](https://github.com/edxi/blog-contribute/issues)这个repo，或者直接克隆repo后创建新文件，然后通过pull request的方式把md文件合并进来。收到新的pull request我会看过文章内容，然后合并进来，并post到网站。
- 当然也接受邮件寄送给我.md文件。<edxi@msn.com>