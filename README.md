# HUIT 公式 web サイト

- ドキュメント準備中
- 編集は、プルリクエストでお願いします。

## 編集者へ

### 編集について

`main` ブランチがサイト（[https://huitgroup.github.io](https://huitgroup.github.io)）即時反映される形になっています。

別のブランチで作業してから、`main` に PR を出す形をとりましょう。

### 記事追加について

年ごとにフォルダを分けています。`_posts/year/` 以下にファイルを作成してください。  
ファイル名は `YYYY-MM-DD-title.md` の形式にしてください。しないと反映されません。

また、以下をファイルの先頭に入れてください。

```md=
---
layout: post
title: ここにタイトル
author: ここにライターのハンドルネーム
image: ここに OGP 画像のパス（なければ、/huit_logo_white.png）
updated_at: ここに更新日時（YYYY-MM-DD）（なければ、この行を消してよい）
---
```

（参考：[https://github.com/jekyll/jekyll-seo-tag/blob/master/docs/usage.md](https://github.com/jekyll/jekyll-seo-tag/blob/master/docs/usage.md)）

### 写真など、静的ファイル

写真などの静的ファイルは、`/assets/` 以下に格納してください。

表示させる際はこのような感じです。 `![alt text](/assets/<year>/<fileName>)`

### ローカルでのプレビュー

`docker-compose` でローカル環境で確認できるようにしました。

`$ docker-compose up` で起動します。

[http://localhost:4000/](http://localhost:4000/activities) で確認することができます。

## その他

Jekyll という Ruby 製の静的サイトジェネレータを使って、GitHub Pages にデプロイされています。

また、GitHub Pages でデフォルトでサポートされている、`slate`というテーマを使用しています。

[https://github.com/pages-themes/slate](https://github.com/pages-themes/slate)

jekyll: [https://jekyllrb.com/](https://jekyllrb.com/)  
liquid（テンプレートタグ）: [https://shopify.github.io/liquid/](https://shopify.github.io/liquid/)

---

詳細は Discord の `#huit_web` まで
