Salonde pure 美容室デモ
======================

千葉県市原市の美容室「サロンドピュア」を想定した
静的HTML / CSSによるデモサイトです。

現在、このプロジェクトはGit / GitHubで管理しています。


■ 制作・公開ワークフロー
------------------------

制作中の正本：
GitHub

確認用公開：
GitHub Pages
https://dr-tonmaruki.github.io/salonde-pure-demo/

正式公開：
Firebase Hosting

各PCではGitHubから clone / pull して最新版を取得し、
修正後は add → commit → push してGitHubへ反映します。


■ 現在の主な仕様
----------------

・Headerロゴ「Salonde pure」に Google Fonts「Lobster」を使用
・HeaderロゴをページTOPへのリンク化
・Header CTAは「電話で予約する」とし、tel: リンクを設定
・お問い合わせブロックにメール導線あり
・SPモノグラムのfaviconを実装
・Footer店名もLobsterで統一
・Hero画像はデモ用画像を使用


■ 注意
------

・メールアドレス info@salonde-pure.example はデモ用です。
  本番時は必ず実在する店舗メールアドレスへ差し替えてください。

・Google Fontsをオンライン取得するため、
  表示確認時はインターネット接続が必要です。

・現在はデモ用として noindex,nofollow を設定しています。
  本番公開時には設定内容を必ず確認してください。

・OGPは未設定です。
  必要に応じて本番公開時に追加します。

・GitHub Pagesはクライアント確認用のデモ公開として使用します。

・正式公開時はGitHub上の最新版を取得し、
  Firebase Hostingへdeployします。

・GA4 / Search Consoleはデモ段階では原則設定せず、
  本番公開時に必要に応じて追加します。