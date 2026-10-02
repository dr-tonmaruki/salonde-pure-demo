Salonde pure 制作・確認用デモ
============================

千葉県市原市青葉台の美容室
「サロンド・ピュア」の公式Webサイト制作・確認用デモです。

静的HTML / CSSで制作し、
Git / GitHubでバージョン管理しています。


■ 公開先
--------

制作・確認用：
GitHub / GitHub Pages

GitHub Pages：
https://dr-tonmaruki.github.io/salonde-pure-demo/

正式公開：
Firebase Hosting

https://salonde-pure.web.app/


■ 制作・公開ワークフロー
------------------------

制作中のHTML / CSSはGitHubで管理し、
確認用としてGitHub Pagesを使用します。

各PCではGitHubから clone / pull して最新版を取得し、
修正後は add → commit → push してGitHubへ反映します。

正式公開時は、
GitHub側で確認した内容を本番用フォルダへ反映し、
Firebase Hostingへdeployします。


■ サイト構成
------------

・1ページ完結型の静的Webサイト
・HTML / CSSによるレスポンシブ対応
・PC / スマートフォン対応
・店舗の実写真を使用
・電話予約を主な問い合わせ導線として設計
・プライバシーポリシーページを設置


■ 主なページ内容
----------------

・Hero
・お店について
・メニュー・料金
・店舗情報・アクセス
・ご予約・お問い合わせ
・プライバシーポリシー


■ 表記
------

日本語店名：
サロンド・ピュア

英字ロゴ：
Salonde pure

所在地：
千葉県市原市青葉台4丁目5-9

電話番号：
0436-61-0096

営業時間：
9:00～17:00

定休日：
土曜日・日曜日・祝日


■ デザイン・実装
----------------

・Headerロゴ「Salonde pure」に Google Fonts「Lobster」を使用
・HeaderロゴをページTOPへのリンク化
・Header CTAは「電話で予約する」
・電話リンクは tel: を使用
・Footerにプライバシーポリシーへのリンクを設置
・SPモノグラムのfaviconを実装
・Hero、店内、道具、外観には実店舗写真を使用
・HeroのH1は
  「市原市青葉台の美容室 サロンド・ピュア」
  とし、ページ内容を明確にしています


■ デモ版と本番版の違い
----------------------

デモ版：
・GitHub Pagesで公開
・検索エンジンへの登録を避けるため
  noindex,nofollow を設定
・GA4は設定しない
・Search Consoleは設定しない

本番版：
・Firebase Hostingで公開
・noindex,nofollow を無効化
・Google Analytics 4（GA4）を使用
・Google Search Consoleへ登録


■ 注意
------

・Google Fontsをオンライン取得するため、
  表示確認時はインターネット接続が必要です。

・GitHub Pagesは制作・確認用として使用します。

・デモ版では noindex,nofollow を維持します。

・本番用のGA4タグや電話クリック計測コードは、
  デモ版には追加しません。

・店舗情報や電話番号などを変更した場合は、
  本番サイト、デモサイト、
  Googleビジネスプロフィール等の表記も確認します。

・公開前後はPC / スマートフォン双方で表示確認を行います。