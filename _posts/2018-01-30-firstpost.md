---
title:  "今更ながらブログ開設"
date:   2018-01-30 12:00:00 +0900
category: objects
tags:
- jekyll
- Github Pages
---

## はじめに
------------

物理学を学ぶときに計算したノートや備忘録をオンライン上に残しておく目的でブログを開いてみた。


## ブログを作るときに見たもの
------------

### 基本的なところ
[GitHub Pages](https://pages.github.com/)と[jekyll](https://jekyllrb.com/)で結構こねくり回せるブログが作れると知って、興味本位から[GitHub Pages](https://pages.github.com/)を選択し。

色々とテーマが用意されているし、公式で用意されてないものでもgithubからforkして持ってくれば良いっぽい。今回はjikoさんのテーマを使わせてもらっています。

<div class="github-widget" data-repo="j-i-k-o/blog"></div>

ブログの基本的な情報は\_config.ymlに入力すればよい。

投稿するときはmarkdownで書いて\_post以下に入れて
```bash
$ git add .
$ git commit -m "nyan"
$ git push
```
とかやればおっけー、とても楽。しかも

```bash
$ jekyll s
```
とすればオフラインでもプレビューが見れる。自宅をオフラインにしている僕としてはとてもありがたい機能。

### すうしき

markdownで書くから[MathJax with Jekyll](http://gastonsanchez.com/opinion/2014/02/16/Mathjax-with-jekyll/)が使えて、みんな大好き\\( \LaTeX \\) 記法で書き込める。

$$ \log J= -2i\int\alpha(x)\frac{e^2}{32\pi^2}\varepsilon^{abcd}F_{ab}F_{cd} $$

ブログで数式書いてそれを\\( \LaTeX \\)ファイルに持ってくことも簡単である。

ただし当然であるが\\( \LaTeX \\)で使えるようなパッケージを使いたかったら最初から\\( \LaTeX \\)で書け、ということはある。

## さいご
-----------

今回はブログで調べたこととかを書いたけれど、多くの記事は物理学っぽいことになるんじゃないかと言う感じ。

あくまで備忘録であり計算ノートなので、行間の詰まり具合は大目に見て欲しいところである。
