# wechat_markdowncss
# Readme

微信公众号一键排版美化

##概要

这是基于[阳志平老师](http://www.yangzhiping.com/tech/r-markdown-knitr.html)分享的，还有[阿禅的可能吧](http://mp.weixin.qq.com/s?__biz=MjM5ODQwMjA4MA==&mid=2649293603&idx=1&sn=57f38200555dcba76d6358594416c089&mpshare=1&scene=1&srcid=11306fdTRqk8EACxnFLwg4Al#rd)分享的内容，这一键排版是通过浏览器插件去实现的，
暂时只做了一个样式而已，还是比较适合技术风格，学术风格和文字生产者的风格的。其他的样式会陆续试试看的、

##缘起

《新闻实验室》的方可成老师在找人美化公众号排版，我就自告奋勇的去帮忙了。主要是看了阿禅的文章后挺想试手的，但在试的时候发现使用 markdown here 的插件就不需要写函数了，就果断选择了这个方式。同时，也觉得这个方式可以复制黏贴快速上手。（嗯，我就是比较懒）


##实现

如果你懂一些计算机知识和英文，你会明白，整个过程无非就是修改 css而已。
但由于微信和 markdown here 都有个别的 css 样式不支持，所以还是有所限制的。

具体的程序实现可以有多种方式。列述于下。

### 1. 学会使用 Markdown 语言
[格式说明](http://markdown.tw/)

###2. 使用 Markdown 语言去写作
写作工具推荐：
[Mweb](http://zh.mweb.im/)

[typora](https://typora.io/)

[moeditor](https://moeditor.org/)

atom 里面装 markdown 插件也可以,不过比较适合 geek 啦

###3. 下载浏览器插件 Markdown here
这个插件是可以将浏览器中编辑器里的 Markdown 文本转换成渲染过后的 HTML。
[安装](http://markdown-here.com/get.html)
###4. 配置 Markdown Here Option
安装成功后，在Markdown Here插件的选项中，选择“基本渲染CSS”，进行部分修改。
css01
###5. 使用 Markdown Here 渲染
把用 markdown 语言写好的文章复制黏贴到微信公众编辑器里，点击插件或快键键（默认快捷键是ALT + CTRL +Z）实现样式就可以了。
###6. 配色
想修改颜色的，可以在这里选色号去修改啦
[地址需翻墙](https://material.io/guidelines/style/color.html#color-color-palette)


