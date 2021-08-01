![image]({{site.baseurl}}/huit_logo_white.png)

<!-- {{site.baseurl}}はレポジトリの設定によっては/sample...で上手く出来ない時があるので必要 -->

# HUIT 北大 IT 研究会

<!-- [English Page](/en.index) -->

<!-- English Page is [here](/en.index).-->

<!-- 日本語わからん人が来たとして、どうするん？ -->
<!-- かっこいい -->

HUIT は、北海道大学の学生を中心とした IT 系学生サークルです。

北海道のエンジニア学生の交流の場になるようなコミュニティを目指して 2017 年から活動しています。

毎週金曜日午後 8 時からの定期的な活動の他、勉強会やハッカソン、LT 大会を開催しています。

<!-- 24時間表記が好き -->

Twitter: [@huitgroup](https://twitter.com/huitgroup)

### 🎉 2021 新歓

2021 新歓は終了しました。たくさんのご参加ありがとうございました！
全 5 回で、延べ 50 人ほどの参加がありました。

HUIT では、いつでも入部を受け付けています。2 ヵ月の体験入部期間でぜひ雰囲気を掴んでください。興味があれば [Twitter の DM](https://twitter.com/huitgroup) まで！

勉強会の飛び入り参加もお待ちしています。

---

## 👨‍💻 これまでの活動

### 2021 年

<ul> <!-- 2021年の記事一覧 -->
{% for post in site.posts %}
    {% capture year %}{{post.date | date: "%Y"}}{% endcapture %}
    {% if post.next %}{% capture nyear %}{{ post.previous.date | date: '%Y' }}{% endcapture %}{% endif %}
    <li>{{ post.date | date: "%m 月 "}}<a href="{{ post.url }}">{{ post.title }}</a></li>
    {% if year != nyear %}{% break %}{% endif %}
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

～今後の予定～

- 08 月 ブログを整備します
- 08 月 OB・OG 合同 LT 大会を開催します
- 12 月 冬の LT 会
- 3 月 HUIT ハッカソン

<br/>

#### [全ての活動記録](/activities)

<br/>

---

### 🛠️ 部員の技術スタック

- Web 制作
  - フロントエンド： `React` `Vue`
  - バックエンド： `Django` `Node.js` `Go` `PHP`
- 競技プログラミング： `C++` `Python`
- ゲーム制作： `Unity`
- ネットワーク・OS： `C` `Rust`
- マイコン・組み込み・IoT： `Raspberry Pi` `Arduino` `ESP` `PIC` `IchigoJam`
- BOT 制作： `Discord` `Twitter`
- 機械学習・AI： `自然言語処理` `画像処理` `音声処理`

### 🎈 部員のイベント参加

- [JPHacks](https://jphacks.com/)（全国大会出場）
- [ISUCON10](https://isucon.net/)
- [N-PTC](https://nttcom.connpass.com/event/201413/)
- [セキュリティ・キャンプ](https://www.ipa.go.jp/jinzai/camp/index.html)
- Global Cybersecurity Camp ([gcc.ac](https://gcc.ac/))
- [Micro Hardening v2](https://microhardening.connpass.com/event/211463/)
- [SecHack365](https://sechack365.nict.go.jp/course/index.html)

---

## ✉️ お問い合わせ

見学希望・イベント共催・その他、Twitter ([@huitgroup](https://twitter.com/huitgroup)) まで DM お願いします！

<a class="twitter-timeline" data-height="600" data-theme="light" href="https://twitter.com/huitgroup?ref_src=twsrc%5Etfw">Tweets by huitgroup</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
