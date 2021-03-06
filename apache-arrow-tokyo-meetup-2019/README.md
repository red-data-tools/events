# Apache Arrow東京ミートアップ2019

## 目的

Apache Arrowユーザーを増やすこと。（開発者は、増えるといいなくらい。）

去年と同じように開発者を増やすことを目的にしようかと思ったが、1.0.0リリースのタイミングなので今回はユーザーを増やす方向で設計する。

## 実現方法

次のことを紹介するイベントにする。

  * Apache Arrowそのもののこと
  * Apache Arrowの利用事例

Apache Arrowそのもののことを知ることでなにができるのか、なにがうれしいか、どこで活用できそうかを参加者が検討できるようにする。参加者が実際に自分のプロダクトで使いたいと思える機会にすることでユーザー増加を狙う。

実際にどうやって使うかまで検討できるように「わかった気になる情報」ではなく「わかる情報」を提供することが重要である。

Apache Arrowの詳細な情報例：

  * [Apache Arrowの最新情報（2018年9月版）](https://www.clear-code.com/blog/2018/9/5.html)
  * [Apache Arrowの最新情報（2019年9月版）](https://www.clear-code.com/blog/2019/9/30.html)

Apache Arrowの利用事例を知ることで参加者が自分も同じように使えるのではないかと検討できるようにする。また、Apache Arrowを使っているプロダクトのユーザーになるというような間接的（？）なユーザー増加も狙う。

利用事例ではApache Arrowあり・なしでどのように違うのか、どのくらい違うのかがわかるようにすることが重要である。これによりApache Arrowのメリットが伝わりやすくなるからである。

## 実施時期

確定：2019年12月11日（水）の夜。

2019年12月または2020年1月。

Apache Arrow 1.0.0が11月末から12月頭くらいにリリースされると予想しているから。Apache Arrowは2ヶ月くらい毎にリリースされており、0.15.0が10月頭にリリースされたので次のリリースである1.0.0は12月頭前後になるだろう。1.0.0リリース直後がベストだがリリース前後なら悪くない。

2019年12月7日（土）はJapan.R 2019があるので避ける。

去年は土曜日に開催したが今年は平日開催も検討する。

## 内容

以下のどちらかの話題のトークで構成する。

  * Apache Arrowそのもの
  * Apache Arrowの利用事例

トークの後に懇親会も開催する。ただの懇親会ではなく、目的の実現に近づくような更新会を設計すること。

### トーク

#### Apache Arrowそのもの

トークのテーマ候補は以下の通り。

  * 最新情報紹介（@kou? @shiro615?）
  * Gandivaまわり（@shiro615?）
  * Rまわり（@yutannihilation）
  * Apache Arrow Datasets C++（@mrkn）
  * ...

#### Apache Arrowの利用事例

  * Apache Spark
  * [PG-Strom](https://heterodb.github.io/pg-strom/ja/) （@kaigai）
  * Chainer（？）
  * Fluentd（？）
  * TensorFlow（？）
  * ...

### 懇親会（要名前検討）

トークの部でApache Arrowの詳細や利用例を聞いて、参加者にはそれぞれ「自分たちならこういう感じで使うと嬉しくなるかも？」と考えてもらう。ざっくりした感じでよい。

懇親会の部（要名前検討）では参加者から検討してもらった内容を出してもらって、Apache Arrowスペシャリストのみんな（トークした人とかすでに使っている人とか）がその利用例をより具体的にするための方法を検討するという時間にするのはどうか。これによりざっくりした感じで考えていた自分たちが使えるかも？案が、より現実的なものになり、実際にユーザーになることにつながることを期待している。

懸念点：

  * 参加者が「自分たちならこういう感じで使うと嬉しくなるかも？」を共有してくれなそう
    * 解決案：トークの部が終わったら10分とか時間をとって、嬉しくなるかも？案をまとめる時間を作り、その時間に明示的に考えてもらう。それを回収して（このリポジトリーのissueに書いてもらうとかtwitterにハッシュタグをつけて書いてもらうとか付箋に書いて壁に貼ってもらうとか）、回収したものから案を抽出して検討するのはどうか
  * ...

## 会場

  * [Speee Lounge](https://tech.speee.jp/entry/2017/05/26/101342)

## 集客

ユーザーになりそうな人たちを集めたい。こんな人たち？

  * Apache Spark/Apache Hadoopユーザー
  * PostgreSQLユーザー
  * TensorFlowユーザー
  * ↑を使っているSIerの人たち？
  * MySQLユーザー
    * PostgreSQLとApache Arrowの連携の効果を見てもらってMySQLでも同じ感じにしたいと思ってもらう
  * 広告事業者
    * たくさんの時系列データを扱っていそう

以下のイベントで宣伝できるとよさそう。

  * ...

## スポンサー

  * 主催：株式会社Speee
  * 後援：
    * 株式会社クリアコード
    * ヘテロDB株式会社
