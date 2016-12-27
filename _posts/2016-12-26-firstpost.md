---
title:  "ブログを作ってみた。"
date:   2016-12-26 12:14:00
category: ブログ
tags:
- jekyll
- Github Pages
---

## はじめに
------------

今更になってブログとかを開設してみた。
せっかく技術的なことをしても、やったことを忘れてしまったら意味が無いので自分の備忘録として使っていくつもり。
過去に作ったものとかも徐々に整理して公開していきたい。
   
ブログのテスト投稿目的や使い方の練習も兼ねて、このブログに使用した技術とかを書いていく。  


## ブログに使った技術
------------

### 全体的なもの

[GitHub Pages](https://pages.github.com/)を参考に、[jekyll](https://jekyllrb.com/)を用いた。最近流行っているらしい。直接レイアウトがいじれるので普通のブログに比べて自由度が格段に高くて良い。

jekyllベースの気に入ったテーマがあれば一からデザインを作らなくてもgithubからforkして持ってくれば良い。このブログは以下のテーマを用いている。

<div class="github-widget" data-repo="niklasbuschmann/contrast"></div>

ブログを投稿するには、\_postディレクトリにアクセスしてmarkdown形式でブログを記述して行けば良い。ローカルな環境にjekyllを導入しておけば

```bash
$ jekyll serve
```

によりブログを投稿する前のプレビューができる。便利。

### 細かいテクニックとか

上のようにgithubリポジトリをヴィジェットの形で貼り付ける際にあたり、以下の記事が参考になった。ありがたや。

<iframe class="hatenablogcard" style="width:100%;height:155px" title="RawGitとGithub wegetを使ってはてなブログでGithubリポジトリへのリンクを素敵に表示する" src="https://hatenablog-parts.com/embed?url=http://blog.monocklab.com/entry/2016/01/06/165304" width="300" height="150" frameborder="0" scrolling="no"></iframe>

数式を使いたいときには[MathJax with Jekyll](http://gastonsanchez.com/opinion/2014/02/16/Mathjax-with-jekyll/)のページを参考にすることで、\\( \LaTeX \\) 記法を用いることができる。こんな感じに。

$$ a^2 + b^2 = c^2 $$

## おわりに
-----------

今回はいったんここまで。文字サイズとかカテゴリー分けの仕組みとかもっといじりたいのでその辺はおいおい調整する予定。
