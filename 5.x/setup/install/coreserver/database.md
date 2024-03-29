---
description: >-
  PortalDots上に保存するデータ（ユーザー情報や参加企画情報など）は、データベース上に保存されます。PortalDotsのインストール前に、あらかじめデータベースを作成しておきます。
---

# ステップ2. データベースを作成する

1. コアサーバーのコントロールパネルにログインします
   * 申込み時に届くメールに掲載されている「アカウント名」「パスワード」「サーバー」でログインできます。
2. 画面左のメニューから「データベース」をクリックします
3. 「新しいデータベースを作成」ボタンをクリックします
4. 「データベース名」と「データベースパスワード」は任意のものを設定します。「データベース名」と「データベースユーザ」は同じもので構いません。ここで入力した「**データベース名**」と「**データベースユーザ**」、「**データベースパスワード**」は、PortalDots をインストールする際に必要です。
5. 「データベースを作成」ボタンをクリックします。
6. 「DATABASE CREATED」という画面が表示されます。この画面内に表示されている「**Database**」、「**Host**」、「**Username**」、「**Password**」を確認、メモしてください。これらの情報は、PortalDots をインストールする際に必要です。

{% hint style="warning" %}
「データベースパスワード」は、他の用途で利用していないパスワードを設定してください。このパスワードが漏洩すると、PortalDotsに保存されたユーザー情報が全て漏洩します。必ずランダムな文字列をパスワードとして設定してください。
{% endhint %}
