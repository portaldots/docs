---
description: コアサーバー上でPortalDotsをセットアップしている間にトラブルが発生した場合、以下をご確認ください。
---

# こんなときはどうする？

## インストール中にエラーが発生したとき <a href="#insutruniergashitatoki" id="insutruniergashitatoki"></a>

* **PortalDots 1 はコアサーバーで動作しません。PortalDots 3 以上をご利用ください。**
* 「MySQL データベース設定」や「メール配信設定」をしようとしてもエラーになる場合、入力したパスワードなどが間違っていないかご確認ください。
  * 「データベースパスワード」と「メールパスワード」は、通常異なるパスワードです。「データベースパスワード」を入力するべきところ「メールパスワード」を入力してしまっているなど、パスワードの入力に誤りがないかご確認ください。
* 「ポータルの情報」設定で設定した「実行委員会のメールアドレス」によっては、「メール配信設定」時にエラーとなることがあります。その場合は、一度「ポータルの情報」設定に戻り、違う「実行委員会のメールアドレス」を設定してみてください。

## 「ポータルの情報」を設定後、PortalDots にアクセスできなくなったとき <a href="#ptarunowoportaldots-niakusesudekinakunattatoki" id="ptarunowoportaldots-niakusesudekinakunattatoki"></a>

SSL の設定をしていない状態で、「ポータルの情報」設定の「https 接続を強制する」にチェックを入れると、PortalDots にアクセスできなくなります。

* SSL の設定をしたにも関わらず PortalDots にアクセスできなくなった場合、サーバー側の SSL 設定の処理が完了していない可能性があります。しばらく待ってから再度 PortalDots にアクセスしてください。
* SSL の設定をしていない場合、「[4. 通信を暗号化するために SSL を設定する(無料)](ssl.md)」に従って SSL の設定をした後、しばらく待ってから再度 PortalDots にアクセスしてください。

## それでも解決しないとき <a href="#soredemoshinaitoki" id="soredemoshinaitoki"></a>

[PortalDots の LINE 公式アカウント](https://lin.ee/aeee9s9)では、PortalDots のセットアップ方法や利用方法に関する質問を受け付けております(無料)。ぜひご活用ください。

{% hint style="warning" %}
PortalDots開発チームはボランティアによる活動です。LINEでのサポートは解決を保証するものではありません。予めご了承ください。
{% endhint %}
