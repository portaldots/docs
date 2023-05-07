# よくある質問

## 🤔 PortalDots について <a href="#portaldots-nitsuite" id="portaldots-nitsuite"></a>

<details>

<summary>Q. PortalDots とは何ですか?</summary>

**A. 学園祭の運営をサポートする、学園祭実行委員会向けのウェブシステムです。**

具体的には、こんなことができます（一例）。

* 学園祭に参加するサークルの方へお知らせメールを一斉配信できます
* 各種申請(参加登録、利用ブースの希望調査、車両入構申請など)の受付をオンラインで行うことができます
* 各種申請フォームは、Google フォームのように直感的に作成できます
* ウェブシステムには学生のみがユーザー登録・ログインできるため、セキュリティを確保できます
* それぞれの参加サークルが利用する教室・ブースなどの場所を管理できます

</details>

<details>

<summary>Q. PortalDots は誰が作っているのですか?</summary>

**A. 開発は東京理科大学の学園祭実行委員経験者が主導するボランティアの開発チームによって行っています。**

PortalDots は元々、学園祭実行委員会の内部で構築したウェブシステムでした。このウェブシステムを多くの学園祭に使っていただきたいと思い、PortalDots という名前で一般公開することにしました。

</details>

<details>

<summary>Q. PortalDots の開発は誰でも関われますか?</summary>

**A. はい、大歓迎です！**

PortalDots のプログラムは [GitHub 上で公開](https://github.com/portaldots/PortalDots)しています。

技術的な話になりますが、要望やバグ報告の Issue やプログラム改修依頼の Pull Request という形で PortalDots の開発に貢献していただけます。

</details>

## 💰 費用について <a href="#nitsuite" id="nitsuite"></a>

<details>

<summary>Q. PortalDots は無料で利用できますか?</summary>

**A. はい、PortalDots のソフトウェア本体は無料で利用できます。ただし、PortalDots を利用するには別途ウェブサーバーが必要です。**

PortalDots は無料で提供しており、どなたでも自由にご利用いただけます。ただし、PortalDots 開発チームが提供するのはPortalDots のプログラムコードのみとなります。実際に PortalDots を利用するには、PortalDots をインストールするためのウェブサーバーが必要です。これは、WordPress などと同様の仕組みです。

</details>

<details>

<summary>Q. ウェブサーバーはどのように用意すれば良いでしょうか?</summary>

**A. PortalDots は一般的な「WordPress 対応レンタルサーバー」に対応しています。**

PortalDots は WordPress に対応したレンタルサーバーにインストールすることができます。具体的には、PHP 8.0 以上かつ MySQL 5.7 以上を搭載したサーバーに対応しています。

</details>

<details>

<summary>Q. レンタルサーバーの費用はどのくらいかかりますか?</summary>

**A. 年間 5,000 円〜10,000 円程度のサービスが多いと思います。**

PortalDots をインストール可能なレンタルサーバー（PHP 8.0 以上、MySQL 5.7 以上を搭載）の価格帯は、おおむねこの金額になるかと思います。

なお、同じレンタルサーバーサービスであっても、一番価格が低いプランでは PortalDots を利用できないことがありますのでご注意ください。

</details>

## 🛠 初期設定について <a href="#nitsuite" id="nitsuite"></a>

<details>

<summary>Q. PortalDots の導入に専門的な知識は必要ですか?</summary>

**A. あまりパソコンに詳しくない場合は、パソコンに詳しい人に導入を頼んでみてください。**

PortalDots は、「登録したらすぐ使えるサービス」ではありません。レンタルサーバーの契約、FTP ソフトの利用方法などにおいて、ある程度 IT に関する知識が必要になります。

とはいえ、プログラミングの知識は必要ありません。[セットアップ方法のマニュアル](setup/install/)では、手順通りに作業を行うことで PortalDots を導入することができるよう、できる限り詳細に説明しています。

</details>

<details>

<summary>Q. PortalDots はどうやって導入するのでしょうか?</summary>

**A. PortalDots に対応したレンタルサーバーを契約し、そのサーバーにインストールすることで導入できます。**

参考として、PortalDots 公式サイトでは[ロリポップ！レンタルサーバー](setup/install/lolipop/)、[コアサーバー](setup/install/coreserver/)に PortalDots をインストールする方法を紹介しています。

また、これら以外のレンタルサーバーでも、おおむね下記の方法で PortalDots をインストールすることができます。

1. PHP 8.0 以上、MySQL 5.7 以上、Apache (または LiteSpeed) に対応したサーバーを用意する
2. サーバー提供会社のマニュアルを参考に、メールサーバーやデータベースサーバーの設定（ホスト名、パスワード、ポート番号など）を確認する
3. [PortalDots をダウンロード](https://www.portaldots.com/download/) し、ZIP ファイルを展開する
4. FTP ソフトなどを利用して PortalDots をサーバーへアップロードする
5. アップロードした PortalDots の URL にアクセスし、表示されるインストーラーの指示に従う
6. インストールが完了したら、メール配信を利用できるように CRON の設定をする (レンタルサーバー会社によって設定方法が異なります。詳細は [PortalDots の LINE 公式アカウント](https://lin.ee/aeee9s9) までお問い合わせください)

</details>

## 💻 運用について <a href="#nitsuite" id="nitsuite"></a>

<details>

<summary>Q. PortalDots はどのように使えば良いでしょうか?</summary>

**A. まずは、各サークルの学園祭担当者に PortalDots のユーザー登録をしてもらいましょう。**

PortalDots を使ってお知らせメールを配信したり、各種申請を受け付けたりするには、各サークルの方に PortalDots へのユーザー登録をしていただく必要があります。

ユーザー登録では学籍番号の入力が必要なため、学外のユーザーが学園祭に参加登録することを防ぐことができます。また、ユーザー登録していただいたユーザーに対してお知らせメールを配信したり、各種申請フォームへの入力をお願いしたりすることができます。

</details>

<details>

<summary>Q. お知らせや各種申請フォームを、各担当の実行委員に作ってもらうには?</summary>

**A. 実行委員の方にも PortalDots のユーザー登録をしてもらいましょう。**

お知らせや各種申請フォームの作成は、PortalDots の「スタッフモード」で行うことができます。

まずは実行委員に PortalDots のユーザー登録をしてもらいます。その後、管理者ユーザーがそのユーザーを「スタッフ」として登録することで、PortalDots の「スタッフモード」が利用可能になります。

</details>

<details>

<summary>Q. ユーザー登録の方法や「スタッフ」登録の方法を知りたい</summary>

**A. 「**[**PortalDots のユーザー登録をしてもらう**](setup/user-registration.md)**」ページをご覧ください。**

</details>

<details>

<summary>Q. 作成した申請フォームがユーザーに表示されない!</summary>

**A. 下記をご確認ください。**

* **申請フォームに回答できるのは、「登録受理状況」が「受理」となっている企画のみです。**
  * 企画参加登録の受付方法や「登録受理状況」を変更する方法は、「[PortalDots を使って企画参加登録を受け付ける](features/circle-registration.md)」ページに記載しています。
* **申請フォームは公開状態になっていますか?**
  * 申請フォームは、ユーザーに対して公開するかどうかを設定できます。申請フォームの設定をご確認ください。

</details>

## ❓ その他 <a href="#sono" id="sono"></a>

<details>

<summary>Q. PortalDots についてわからないことがあるときは?</summary>

**A. PortalDots 開発チームまでお気軽にお問い合わせください！**

[PortalDots の LINE 公式アカウント](https://lin.ee/aeee9s9) では、PortalDots のセットアップ方法や利用方法に関する質問を受け付けております(無料)。ぜひご活用ください。

※PortalDots 開発チームはボランティアによる活動です。LINE でのサポートは解決を保証するものではありません。予めご了承ください。

</details>
