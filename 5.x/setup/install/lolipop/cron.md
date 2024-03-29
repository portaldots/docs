---
description: 「お知らせ」をユーザー全員に一斉配信するためには、CRONの設定が必要です。
---

# ステップ6. メールの一斉配信機能のセットアップ(CRONの設定)

1. CyberduckでサーバーにFTP接続します
2. Cyberduckの画面上の cron フォルダをダブルクリックして開きます
3. `lolipop.sh.sample` というファイルを右クリックし、「名前の変更」をクリックします
4. 名前を入力できるようになったら、「`lolipop.sh.sample`」を「`lolipop.sh`」に変更し、Enterキーを押します
5. 「名前したファイルを移動しますか？」と表示されたら「名前を変更」をクリックします
6. 「`lolipop.sh`」を右クリックし、「エディタで編集」を選択し、表示されるプログラム名(メモ帳など)をクリックします。
7. ファイル内の「PortalDotsのフォルダ」と書かれている箇所を削除し、代わりに ホームディレクトリのパスを入力してください。入力できたらファイルを保存してください。自動的にサーバーへアップロードされます。
    * ホームディレクトリのパスは、「ロリポップ！ユーザー専用ページ」内で確認できます。画面左のメニューから「ユーザー設定」を選び、「アカウント情報」をクリックした後に表示される「フルパス」が、ホームディレクトリのパスです。
8. `lolipop.sh` を右クリックし、「情報」をクリックします
9. 「アクセス権」タブを開き、「オーナー」という行にある「実行」にチェックを入れます。\
   ![](<../../../.gitbook/assets/image (13).png>)
10. 「ロリポップ！ユーザー専用ページ」にログインします
11. 画面左のメニューから「サーバーの管理・設定」を選び、「cron設定」をクリックします
12. 以下のように入力します。
    * 「cronの設定名」には「PortalDots」と入力します。
    * 「日付（月）」では「毎月」を選択します。
    * 「日付（日）」では「毎日」を選択します。
    * 「曜日」では「毎日」を選択します。
    * 「時間（時）」では「毎時」を選択します。
    * 「時間（分）」では「10分毎」を選択します。
13. 「スケジュール」欄に「10分毎 のスケジュールで実行します」と表示されたことを確認します。
14. 「実行ファイルパス」には「cron/lolipop.sh」と入力します。
15. 「設定」ボタンをクリックします。
16. 以上でCRON設定は完了です。「お知らせ」の一斉配信機能が利用可能になります。

以上でPortalDotsのインストールは完了です！お疲れ様でした！
