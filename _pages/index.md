---
title: "HUIT 北大IT研究会"
# classes: wide
permalink: /
---

<!-- ![image]({{ "/assets/images/huit_logo_white.png" | relative_url }}) -->

<!-- {{site.baseurl}}はレポジトリの設定によっては/sample...で上手く出来ない時があるので必要 -->

<!-- # HUIT 北大 IT 研究会 -->

<!-- [English Page](/en.index) -->

<!-- English Page is [here](/en.index).-->

<!-- 日本語わからん人が来たとして、どうするん？ -->
<!-- かっこいい -->

# HUIT とは

HUIT は、北海道大学の学生を中心とした IT 系学生サークルです。

北海道のエンジニア学生の交流の場になるようなコミュニティを目指して 2017 年から活動しています。

毎週金曜日午後 6 時からの定期的な活動の他、勉強会やハッカソン、LT 大会を開催しています。

<!-- 24時間表記が好き -->

Twitter : [@huitgroup](https://twitter.com/huitgroup)

<br/>

# 👨‍💻 これまでの活動

## 2022 年

<ul> <!-- 2022年の記事一覧 -->
{% for post in site.posts reversed %}
    {% capture year %}{{ post.date | date: "%Y" }}{% endcapture %}
    {% assign currentYear = 'now' | date: "%Y" %}
    {% if currentYear == year %}
      <li>{{ post.date | date: "%m 月 "}}<a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
{% endfor %}
</ul>

<!-- - 5 月 新入生向け勉強会
  - 5/21 ネットワーク勉強会（予定）
  - 5/28 機械学習勉強会（予定）
  - 6/4 Web エンジニアになろう（予定）
  - 6/11 開発と Docker（予定） -->

---

～終了した活動～

- 03 月 HUIT ハッカソン開催
- 04 月 部の discord の管理に bot を作ってみた
- 06 月 集中講義「プログラミング教室」の TA を派遣しました
- 07 月 夏だ！花火だ！LT だ！ HUIT × ビズリーチコラボ LT 大会
- 12 月 [2021 年 HUIT アドベントカレンダー](https://qiita.com/advent-calendar/2021/huit)

～今後の予定～

<br/>

---

#### [これまでの活動記事](/activities)

<br/>

# 🛠️ 部員の技術スタック

- Web 制作
  - フロントエンド： `Next.js` `React` `Vue` `Jekyll`
  - バックエンド： `FastAPI` `Django` `Docker` `Node.js` `Go` `PHP` `Firebase`
- 競技プログラミング： `C++` `Python`
- アプリ： `Flutter` `Android` `iOS`
- Windows アプリケーション制作： `C#`
- ゲーム制作： `Unity`
- ネットワーク / OS： `C` `Rust`
- マイコン / 組み込み / IoT： `Raspberry Pi` `Arduino` `ESP` `PIC` `IchigoJam`
- バージョン管理： `Git` `Github`
- BOT 制作： `Discord` `Twitter`
- 機械学習 / AI： `自然言語処理` `画像処理` `音声処理`
- ブロックチェーン： `NFT` `Solidity`
- CG： `Blender` `Fusion`
- Latex

<br/>

# 🎈 部員のイベント参加

- ハッカソン
  - [技育展](https://talent.supporterz.jp/geekten/2021/)
  - [JPHacks](https://jphacks.com/)（全国大会出場）
  - てくのこ SCSK 株式会社主催
  - [SAPPORO CITY HACK](https://mikan-hchp.connpass.com/event/240964/)
- セキュリティ
  - [SecHack365](https://sechack365.nict.go.jp/course/index.html)
  - [セキュリティ・キャンプ](https://www.ipa.go.jp/jinzai/camp/index.html)
  - [セキュリテイミニキャンプ](https://www.security-camp.or.jp/minicamp/online2021.html)
  - [Micro Hardening v2](https://microhardening.connpass.com/event/211463/)
  - Global Cybersecurity Camp ([gcc.ac](https://gcc.ac/))
- 競プロ
  - [ICPC アジア地区予選](https://icpc.iisf.or.jp/2020-yokohama/)
  - [ICPC](https://icpc.iisf.or.jp/)
  - [Google Code Jam](https://codingcompetitions.withgoogle.com/codejam)
  - [AtCoder](https://atcoder.jp/?lang=ja)
- CG コンテスト
  - Fusion 360 学生デザインコンテスト
  - Fusion 360 Virtual Academic Design League
  - [Generative Design Award](https://www.myautodesk.jp/f360-gd-contest-2021/)
- LT 会
  - [技育祭 2022 春 学生 LT](https://talent.supporterz.jp/geeksai/2022spring/)
  - [北海道未完 × デルタ新潟合同 LT 会](https://hokkaido-mikan-delta-niigata. connpass.com/event/236750/)
  - [未完 LT 会](https://mikan-study.connpass.com/event/233759/)
- CTF
  - [WaniCTF2021](https://wanictf.org/)
  - nitic_ctf_2
  - [SECCON CTF 2021](https://www.seccon.jp/2021/)
  - [LINE CTF 2022](https://score.linectf.me/)
- その他
  - [ISUCON10](https://isucon.net/)
  - [N-PTC](https://nttcom.connpass.com/event/201413/)
  - [バーチャル雪まつり 2021 主催](https://www.value-press.com/pressrelease/264864)
  - [Kaggle](https://www.kaggle.com/)
  - [ICTSC](https://icttoracon.net/)
  - [北大 DX フェローシップロゴデザイン](https://sites.google.com/eis.hokudai.ac.jp/dxphd-fellow/logo)
  - [STAND OUT](https://standout-sapporo.city/)

<br/>

# FAQ

**Q. 初心者でも入れますか？**

A. 入れます！「 IT って面白そうだな」という気持ちさえあれば完璧です。基礎から上級レベルまで本当に色んなことを教えてくれる人たちがたくさん集まっています

---

**Q. もう上級生なのですが …**

A. 問題ありません！3 年生以上 (院生含む) から入部する方はよくいますし、十分馴染んでいける環境が整っていると思います

---

**Q. 他大学でもいいですか？**

A. もちろんです！実際 2021 年度の部長は他大学であるように、とても寛容な雰囲気です！

---

**Q. 年度の途中からでも入れます？**

A. ＯＫです！昨年度は半分以上の方が 4 月以外に体験入部をしに来てくれました

---

**Q. 文系でも入れる？**

A. 文系も大歓迎です！たしかに情報系の知識は多少あるといいですが、それは入部後に本を読んだり詳しい人に聞いていけば十分に補っていけます（文系より）

---

**Q. 辞めてしまったけど、もう一度入っていいですか？**

A. どうぞいつでも帰ってきてください！お待ちしています！

---

**Q. いつどこで活動しているんですか？**

A. 毎週金曜日 18 時 (オンラインの時は 20 時) から定期的に集まっています。現在は 13LABO というコワーキングスペースを主に使って活動しています！オンラインでは Discord というボイス & チャットツールを用いています。

---

**Q. 金曜の 18 時は予定が合わなさそうです …**

A. 問題ありません！金曜の 18 時に集まってしていることは、 1 週間どんなことをしていたかということを共有する程度であり、これに出られないからといって輪の中に入っていけないということは無いです。むしろ不定期のイベントに顔を出せると技術的に圧倒的成長しつつメンバーとも交流できます！

---

**Q. どんなイベントがあるんですか？**

A. HUIT としては LT 会 (ショートプレゼン) 、勉強会、ハッカソンなどのイベントを主催したり企業さんなど他団体と共催したりしています。 <br/>
HUIT 外部のイベントとしては上記の [部員のイベント参加](/#-%E9%83%A8%E5%93%A1%E3%81%AE%E3%82%A4%E3%83%99%E3%83%B3%E3%83%88%E5%8F%82%E5%8A%A0) を見ていただければある程度は分かるかと思いますが、これでもまだまだ IT 系のイベントを網羅しているとは言えないほど、その数は非常に充実しています！

---

**Q. 入ると良いことはありますか？**

A.

- 周りに仲間がいるのでモチベーションが上がります
- チーム開発が出来ます
- IT についてお話できます
- 分からないことを教えてもらえます
- いろいろな IT 系のイベントに一緒に出られます！
- 「ちょっと面白いこと始めてみたい」のキッカケを得られます！

---

**Q. 他のサークルと両立出来ますか？**

A. できます！全てのイベント・活動が任意参加となっているので自分で忙しさをコントロールできます

---

**Q. 部員はどんな技術を使用していますか？**

A. 上記の [部員の技術スタック](/#%EF%B8%8F-%E9%83%A8%E5%93%A1%E3%81%AE%E6%8A%80%E8%A1%93%E3%82%B9%E3%82%BF%E3%83%83%E3%82%AF) をご覧ください。

---

**Q. お試し期間はありますか？**

A. HUIT では最大 2 ヵ月の体験入部が可能です。部費を支払うことによって本入部することができます。

---

**Q. 部費はどのくらい？**

A. 年間 2000 円 (半期 1000 円) です。

---

**Q. 分からないことが …**

A. 公式 Twitter ([@huitgroup](https://twitter.com/huitgroup)) の DM ・質問箱にてお問い合わせください。何でも答えます！

<br>

# ✉️ お問い合わせ

見学希望・イベント共催などについては、Twitter ([@huitgroup](https://twitter.com/huitgroup)) まで DM お願いします！

<div style="width: 80%;margin: auto;">
<a class="twitter-timeline" data-height="600" data-theme="light" href="https://twitter.com/huitgroup?ref_src=twsrc%5Etfw">Tweets by huitgroup</a>
</div>
 <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
