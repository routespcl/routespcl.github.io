+++ 
date = 2022-12-20
title = "hugo + coder でフォントに詰まった"
description = ""
slug = ""
authors = []
tags = ["Tech"]
categories = ["Blog"]
externalLink = ""
series = []
+++

## tl;dr
初めて作ったWebサイトのフォントがおかしかったのでネットに転がっていた備忘録通りにstatic/css/custon-font.cssを追加したがなぜかうまくいかず、assets/css/custom-fonts.cssにスタイルシートを移動したらうまくいった。

## 参考
* [ブログ移行日記(その3) - Hugoの設定と微調整(テーマに合わせた)](https://blog.johtani.info/blog/2020/01/24/setting-hugo)
* [Hugo + LoveItでWebサイトを作る](https://toruniina.github.io/ja/posts/building-a-website-powered-by-hugo-and-loveit/)
* [hugo-coderで日本語フォントを設定する](https://mtb-production.info/posts/2021/08/27/3418a64c-0690-11ec-ae7d-1e00ea01df3a/)
* [nil pointer evaluating resource.Resource.RelPermalink(GitHub)](https://github.com/luizdepra/hugo-coder/issues/685)