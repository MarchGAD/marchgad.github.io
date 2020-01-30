---
layout: post
title: "Hello Github Pages"
date: 2020-01-30
excerpt: "建个博客真是费心费力"
comments: false
---

# 主题

参考[如何在GitHub上写博客？](https://www.zhihu.com/question/20962496)
在推荐的[http://jekyllthemes.org/](http://jekyllthemes.org/)主题站中好不容易才翻到了现在的主题[Moon](http://taylantatli.github.io/Moon)

之前找的主题，有的是没有post文件，有的是jekyll版本不对头。

而现在的主题，在我win10本地也跑不起来，一直会报如下错误：
~~~ruby
  Liquid Exception: An existing connection was forcibly closed by the remote host. - SSL_connect in F:/BOOKS/BLOG/marchgad.github.io/_posts/2013-08-16-code-highlighting-post.md
~~~

在github pages上其实也不对劲，经历了如下阶段：
1. `_config.yml`没生效，/home/页面的所有链接依然指向原博主的页面。
2. 只有/home/页面有效果，/posts/、/about/、/projects/的页面效果没起效，全是白板。
3. /posts/页面依旧是白板。
4. /posts/页面不是白板了，但点击文章后无法阅读，全报404
5. 然后全部正常了。。。
在这期间我一直努力在本地调试，没对git那儿做任何操作，就给我整好了？好了？

好了就好。不管了。