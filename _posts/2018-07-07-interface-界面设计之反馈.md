---
title:  "界面设计之反馈"
modified: 2018-06-26 T16:03:49-04:00
categories: 
  - 界面设计
tags:
  - 笔记
---

{% include base_path %}

{% include toc title="目录" %}


## 界面设计之反馈

## 内联404错误

一开始做导航内链的时候，在网站上点开只有about点开后出现页面，而其他的点开都是404错误。在这种情况下，我还是不断的尝试，因为开始我认为是我的路径错了，但尝试很多次后发现路径是对的，其实是一开始的链接出现了错误。

![网址](https://gitee.com/lishanshan33/minimal-mistakes/raw/master/images/网址.PNG){: .align-center}

而且在_config.yml里格式，还是格式特别重要，在确保网站网址是正确的基础下，还要主要双引号“”有没有加上。如果没有双引号，网页都是显示不出来的。

- 而且做网站真的是一步错，万步错。虽然一开始的网址错误没有造成很严重的影响，像404错误或者说无法部署，但这样的小错误对接下来的步骤还是有很大的影响的，就像因为这个404错误，尝试了很多次还是无果而且很难找到错误的原因，这样会浪费很多时间和精力。所以说在开始做项目做网站是一定要认真仔细，要确保每一步都是正确的，才能对后面的步骤更轻松些。

## 图片无法显示

![图片错误](https://gitee.com/lishanshan33/minimal-mistakes/raw/master/images/图片错误.PNG){: .align-center}

在编辑笔记中，想要加入图片，使用了多种方法还是失败。最开始是使用了最简单的路径方法。失败。

![图片链接](https://gitee.com/lishanshan33/minimal-mistakes/raw/master/images/图片链接.PNG){: .align-center}

然后尝试了用图片链接的方面，还是失败。

![images](https://gitee.com/lishanshan33/minimal-mistakes/raw/master/images/images.PNG){: .align-center}

最后在同学的帮助下，发现图片需要备份两份，则需要在minimal-mistakes里新建一个raw文件，再在raw文件中新建一个master文件，然后还要在master文件中新建一个images文件，然后把文件放进这个images文件夹里的同时，还需要复制一份到minimal-mistakes的images文件夹中，最后图片才得以显示。而且在在一过程中，文件名的不符都会造成图片显示不出，我对于这个操作感到惊讶和神奇，但是仍然不懂为什么这样才可以显示出图片，很好奇原理是什么。
