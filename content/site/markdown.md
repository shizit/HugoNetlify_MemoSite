+++
title = "MarkDown"
weight = 15
+++

---
## 〇MarkDownとは  

+ #### 概要

    MarkDownとはHTMLに変換できる文章の書き方（マークアップ言語）です。    
    指定されたマークをつけることで（例えば太字にする文字は前後に**をつける、など）   
    パーサーがHTMLに変換してくれます(```**太字**``` ⇒```<b>太字</b>``` )。  

　

+ #### 長所

    >* 手軽に文章構造を明示できる
    >* 簡単で覚えやすい記述
    >* 読み書きに特別なアプリを必要としない
    >* それでいて、対応アプリを使えば快適に読み書きできる　  
    >　  
    >**引用**：日本語Markdownユーザー会 -> Markdownとは  
    >　　　[https://www.markdown.jp/what-is-markdown/](https://www.markdown.jp/what-is-markdown/)

　

## 〇MarkDownの表現 

+ #### 文字効果

    **BOLD**
    ``` markdown
    **BOLD**  //**を前後に2つずつつけます
    ```

    _ITALIC_  
    ``` markdown
    _ITALIC_  //_を前後につけます
    ```  

    ~~Strike Line~~
    ``` markdown
    ~~Strike Line~~  //~~を前後に2つずつつけます
    ```    
　

+ #### コード
    ``` java
    int i = 0;
    ```

    ```` markdown
    ``` 
    int i = 0;  //`を前後に3つずつ付けます　※マークをエスケープする場合は4つずつ
    ```
    ````
　

+ #### ブロッククオート

    >Blockquotes

    ``` markdown
    >Blockquotes
    ```
　

+ #### テーブル

    |header1|header2|header3|
    |:--:|:--:|:--:|
    |a|b|c|  

    ``` markdown
    |header1|header2|header3|
    |:-:|:-:|:-:|  //「:--」左寄せ　「--:」右寄せ　「:-:」中央寄せ
    |a|b|c|  
    ```
　

+ #### Note
  {{% notice note %}}
  Noteやその他メッセージボックス(info,tip,warning)はHugoのShortCodeを利用して記述します。  
  ShortCodeについては、下記サイトを参照：  
  [https://gohugo.io/content-management/shortcodes/](https://gohugo.io/content-management/shortcodes/)  
  {{% /notice %}}

+ #### Info
  {{% notice info %}}
  information
  {{% /notice %}}

+ #### Tip
  {{% notice tip %}}
  tip
  {{% /notice %}}

+ #### Warning
  {{% notice warning %}}
  warning
  {{% /notice %}}

　

## 〇その他参考サイト 

>+ メモ書きやドキュメント作成に便利な「Markdown記法」を使ってみよう  
> [https://www.asobou.co.jp/blog/bussiness/markdown](https://www.asobou.co.jp/blog/bussiness/markdown)
>　
>+ Qiita マークダウン記法 一覧表・チートシート  
> [https://qiita.com/kamorits/items/6f342da395ad57468ae3](https://qiita.com/kamorits/items/6f342da395ad57468ae3)  
>
