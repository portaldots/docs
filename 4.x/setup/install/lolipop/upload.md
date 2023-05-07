---
description: データベースとメールサーバーの確認ができたら、いよいよPortalDotsをサーバーへアップロードします。
---

# ステップ4. PortalDotsをサーバーにアップロードする

{% hint style="info" %}
ブラウザ上で利用できる「ロリポップ！FTP」では PortalDotsをアップロードできません
{% endhint %}

1. 「ロリポップ！ユーザー専用ページ」にログインします
2. 画面左のメニューから「ユーザー設定」を選び、「アカウント情報」をクリックします
3. 「サーバー情報」にある「**FTPSサーバー**」「**FTP・WebDAVアカウント**」「**FTP・WebDAVパスワード**」を確認、メモします
   * 「FTP・WebDAVパスワード」は、「表示」ボタンを押すと確認できます。
4. FTPソフトでFTP接続します。FTPソフトをインストールしていない場合、Cyberduckがお勧めです。設定方法はロリポップ！レンタルサーバーのサポートページに掲載されています([Macの場合](https://lolipop.jp/manual/hp/m-cyberduck/) / [Windowsの場合](https://lolipop.jp/manual/hp/w-cyberduck/))。
   * Cyberduckの場合、「環境設定」内の「ブラウザ」タブにある「'.'で始まるファイルを表示」にチェックを入れてください\
     ![](<../../../.gitbook/assets/image (2) (1).png>)
5. 初期状態では welcome.html というファイルが設置されています。不要なため、welcome.html を右クリックして削除します。
6. [PortalDots.zip](https://github.com/portaldots/PortalDots/releases/latest/download/PortalDots.zip) をダウンロードし、展開します。
7. 展開してできたフォルダの中身を全てアップロードします。Cyberduckの場合、Finder(macOSの場合)またはエクスプローラー(Windowsの場合)からファイルをドラッグ&ドロップしてください。
   * 隠しファイル(ドットで始まるファイル)も含めてアップロードしてください。macOS や Linux などの OS では、デフォルトではこれらのファイルは非表示になっています。macOS の場合、Finder で Command + Shift + . を押すと隠しファイルが表示されます。\
     ![](<../../../.gitbook/assets/image (3) (1) (1).png>)
8. アップロードには5分〜10分程度時間がかかりますので、お待ちください。
9. アップロードが完了したら、ロリポップのユーザー専用ページ上部に表示されている「ロリポップ！のドメイン」のURLにアクセスします。この際、URLの先頭に「https://」をつけてアクセスしてください。
   * 「ロリポップ！のドメイン」が「 〇〇.capoo.jp 」の場合、「 [https://〇〇.capoo.jp](https://xn--w6ja.capoo.jp) 」にアクセスしてください。
10. 「PortalDotsへようこそ！」という画面が表示されたら、アップロード完了です。

![](<../../../.gitbook/assets/image (4) (1) (1).png>)
