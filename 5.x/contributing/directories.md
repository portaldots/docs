---
description: PortalDotsを構成するディレクトリ構造を説明します。
---

# PortalDotsのディレクトリ構造

[PortalDotsのGitHubリポジトリ](https://github.com/portaldots/PortalDots)は、以下のディレクトリ構造を持ちます(2023年5月現在)。

PortalDotsは、主にLaravelとVue.js(バージョン3)、SCSSを利用しています。

{% hint style="warning" %}
Laravelのモデルは、一般的に`app/Models`ディレクトリに格納しますが、PortalDotsでは`app/Eloquents`ディレクトリに格納しています。
{% endhint %}

```
.
├── .github
│   ├── workflows           CIの実行やリリースZIPファイルの作成のためのGitHub Actionsワークフロー。
├── app                     Laravelのアプリケーションディレクトリ。
│   ├── Auth                
│   ├── Console             
│   ├── Eloquents           モデル。Laravel標準のフォルダ(Models)とは異なるので注意。
│   ├── Exceptions          
│   ├── Exports             CSVエクスポート/インポート機能。
│   ├── GridMakers          スタッフモード内に表示する各種一覧表示の定義。
│   ├── Http                
│   │   ├── Controllers     コントローラー。原則として1コントローラにつき1アクションのみ。
│   │   ├── Middleware      
│   │   ├── Requests        フォームリクエストクラス。バリデーション処理は原則ここに書く。
│   │   └── Responders      
│   ├── Mail                
│   ├── Notifications       
│   ├── Policies            
│   ├── Providers           
│   └── Services            サービスクラス。データベースを操作する処理をここに書くことがある。
├── bootstrap               
├── config                  
├── cron                    
├── database                
│   ├── factories           
│   ├── migrations          
│   └── seeders             
├── docker_dev              
├── patches                 npmパッケージにパッチを当てるために利用。
├── resources               
│   ├── img                 
│   ├── js                  
│   │   ├── forms_editor    フォームエディター用のJavaScriptファイル。Vue.jsを使用。
│   │   └── v2              フォームエディター以外のJavaScriptファイル。Vue.jsを使用。
│   ├── lang                
│   ├── sass                
│   │   └── v2              主なスタイルはこのフォルダ内に書く。
│   └── views               ビューファイル。原則としてコントローラのアクション1つにつき1ファイル。
└── routes                  ルーティング定義ファイル。スタッフモードと一般モードでファイルを分けている。
```
