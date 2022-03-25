---
title: ブログを整備しました
author: takapiro99
image: /huit_logo_white.png
---

### 経緯

HUIT では、勉強会、LT 会、ハッカソン、並びに企業とのコラボイベントを開催してきました。

それぞれの様子は公式 Twitter（[@huitgroup](https://twitter.com/huitgroup)）や部員の Twitter で発信してきましたが、まとまってアウトプットできる場所がないという課題を抱えていました。

> （該当 issue）[https://github.com/HUITGroup/meeting/issues/44](https://github.com/HUITGroup/meeting/issues/44)

活動内容を後に残したり、より多くの人に活動を知っていただきたいと思い、このホームページ上に markdown で記事を投稿できるようにしました。

<br/>

### やり方

このページは、`GitHub Pages` のテーマを用いて作られています。中身は `Jekyll` という `Ruby` 製の静的サイトジェネレータで作られており、今回は、その posts 機能を使って組み込みました。

[https://jekyllrb.com/docs/posts/](https://jekyllrb.com/docs/posts/)

\_posts というディレクトリの中に markdown を書いていくと、よしなに記事として認識されてくれます。ほぼデフォルトで動かすことができるので、とても簡単です。

[https://github.com/HUITGroup/huitgroup.github.io/tree/main/\_posts](https://github.com/HUITGroup/huitgroup.github.io/tree/main/_posts)

<br/>

### 工夫した点

##### ・簡単にプレビューできる

テーマの通りプレビューするには Ruby と jekyll の環境が必要で少々めんどくさいのですが、docker さえあればコマンド一発でプレビューができるようにしました。

##### ・記事一覧ページの実装

[/activities](/activities) で記事一覧を見ることができます。

ここで、年ごとに自動で仕分けして表示するようにつくりました。

jekyll に使われている liquid というテンプレート言語で実装しました。（実装は[こちら](https://raw.githubusercontent.com/HUITGroup/huitgroup.github.io/main/activities.md)）

<br/>

### さいごに

ここまで読んでくれてありがとうございました！

今後も HUIT をよろしくお願いします。
