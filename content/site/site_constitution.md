+++
title = "概要"
weight = 15
+++

---
## 〇サイトの作成

+ #### **サイト概要**

    メモをMarkDownで記述しGitHubにプッシュすると、  
    当サイトへ自動的に反映される仕組みになっています。
    　  
    　

+ #### **利用したサービス**

  - **[ソース管理：GitHub](https://github.co.jp/)**  
    ソースをオンラインで管理できるサービスです。  

  - **[サイトジェネレータ：HUGO](https://gohugo.io/)**  
    記事などのコンテンツを追加するだけでデザインされたサイトをビルドしてくれる、静的サイトジェネレータです。  

  - **[ホスティング：netlify](https://www.netlify.com/)**  
    GitHubのリポジトリを監視し、自動でWebサイトをデプロイしてくれるホスティングサービスです。
    　  
    　 


+ #### **構成のイメージ図**

![SiteConstitution](https://github.com/shizit/images/blob/master/SiteConstitution.png?raw=true)


+ #### **手順概要**

  1. HUGOをインストール
  2. ローカル環境にHugoのプロジェクトを作成
  3. HugoのプロジェクトにMarkDownの記事を追加
  4. Gitローカルリポジトリ作成
  5. リモートリポジトリ(GitHub)作成
  6. Hugoプロジェクトをリモートリポジトリ（GitHub）へプッシュ
  7. リモートリポジトリをnetlifyと連携
  8. netlifyの設定でデプロイ時にHugoのビルドコマンドを実行するよう設定
  　  
  　

　


