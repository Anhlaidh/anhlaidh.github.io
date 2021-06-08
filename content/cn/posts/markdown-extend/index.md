---
title: "Markdown Extend"
date: 2021-06-08T20:58:36+08:00
draft: false
# weight: 1
# aliases: ["/first"]
tags: ["first"]
author: "Me"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
hidemeta: false
comments: false
description: "Desc Text."
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/<path_to_repo>/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---




## 哔哩哔哩视频

{{< bilibili id=BV1bg4y1q7es >}}

>https://yyqx.online/posts/hugo博客latex渲染/)

## Mermaid

{{< mermaid >}}
sequenceDiagram
    participant Alice
    participant Bob
    Alice->John: Hello John, how are you?
    loop Healthcheck
        John->John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail...
    John-->Alice: Great!
    John->Bob: How about you?
    Bob-->John: Jolly good!
{{< /mermaid >}}

## Latex


行内样式：$x=2$

代码块：
$$
f(x)=\int_{-\infty}^\infty\widehat f\xi\,e^{2\pi i\xi x}\,d\xi
$$


## 网易云音乐

### 单曲：

{{<music netease song 1499600687>}}



### 歌单：

{{<music netease playlist 6764497041>}}

## admonition
{{< admonition type=tip title="This is a tip" open=false >}}
一个 **技巧** 横幅
{{< /admonition >}}
或者
{{< admonition tip "This is a tip" false >}}
一个 **技巧** 横幅
{{< /admonition >}}
