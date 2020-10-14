+++
title = "SpringBoot"
weight = 1
+++

---

## 〇例外処理  

#### 404、500エラー  

  **■概要**  
  404や505のHTTPステータスコードが表示されるエラーは、所定の位置にHTMLファイルを設定すると発生時にそのファイルが読み込まれます。  
　  
  **■設定方法**  
  1. src/main/resources/templatesにerrorフォルダを作成  
  2. フォルダ内にステータスコードに対応した名前のHTMLファイルを作成  
　  
  **■コード(src/main/resources/templates/error/404.html)**  

    ```
    <body>
    h1 th:text="${status}+' '+${error}">404 Not Found</h1>>
    <p>The requested URL was not found on this server</p>
    <p><a th:hre="@{/inquiry">Back to index</a></p>
    </body>
    ```
    　  
  
  　  
  　

　


