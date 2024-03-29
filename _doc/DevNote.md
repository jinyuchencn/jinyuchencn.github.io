## 咋跑

```

$ jekyll build
# => 当前文件夹中的内容将会生成到 ./_site 文件夹中。

$ jekyll build --destination <destination>
# => 当前文件夹中的内容将会生成到目标文件夹<destination>中。

$ jekyll build --source <source> --destination <destination>
# => 指定源文件夹<source>中的内容将会生成到目标文件夹<destination>中。

$ jekyll build --watch
# => 当前文件夹中的内容将会生成到 ./_site 文件夹中，
#    查看改变，并且自动再生成。

$ jekyll serve
# => 一个开发服务器将会运行在 http://localhost:4000/
# Auto-regeneration（自动再生成文件）: 开启。使用 `--no-watch` 来关闭。

$ jekyll serve --detach
# => 功能和`jekyll serve`命令相同，但是会脱离终端在后台运行。
#    如果你想关闭服务器，可以使用`kill -9 1234`命令，"1234" 是进程号（PID）。
#    如果你找不到进程号，那么就用`ps aux | grep jekyll`命令来查看，然后关闭服务器。[更多](http://unixhelp.ed.ac.uk/shell/jobz5.html).

$ jekyll serve --no-watch
# => 和 `jekyll serve` 一样，但不会监测变化。

```

## _config.yml的配置参数

直接去教程翻阅吧
[jekyll doc](http://jekyllcn.com/docs/configuration/)

## _posts的配置

```

---
layout: post
title: 「知乎」如何理解 <code>document</code> 对象是 <code>HTMLDocument</code> 的实例？
subtitle: Why is <code>document</code> an instance of <code>HTMLDocument</code>?
author: "Hux"
header-style: text
tags:
  - Web
  - 知乎
---

```