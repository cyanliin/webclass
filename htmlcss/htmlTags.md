# HTML 常用標籤
HTML 裡有許多預設好的標籤，例如 html, body, title 之類的。有些標籤帶有一些預設的樣式或作用。

|標籤|說明|備註|
|---|---|---|
|&lt;html>|網頁|
|&lt;head>|網頁設定區|
|&lt;body>|內文區|
|&lt;h1>~&lt;h6>|標題|大 -> 小
|&lt;p>|段落|
|&lt;u>|底線|<u>abc</u>
|&lt;i>|斜體|<i>abc</i>
|&lt;strong>|粗體|<strong>abc</strong>
|&lt;div>|區域|用於排版
|&lt;span>|區域|用於排版(不換行)
|&lt;br />|換行|無結束標籤


## 範例
```html
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width,initial-scale=1">
        <title>我的網站</title>
    </head>
    <body>
        <h1>軟體設計</h1>
        <p><strong>軟體設計</strong>是程式設計師<u>按照特定順序撰寫電腦資料和指令的集合</u>。</p>
        <p>「軟體設計」可以是撰寫最基礎的二進制0和1位元；也可以是建立在位元之上的<i>各類軟體語言</i>、演算法、架構、程式、圖像化程式碼來進行。</p>
    </body>
</html>
```

<br />

<div style="border: 1px solid #ddd; padding: 30px; border-radius: 6px;">
<h1>軟體設計</h1>
<p><strong>軟體設計</strong>是程式設計師<u>按照特定順序撰寫電腦資料和指令的集合</u>。</p>
<p>「軟體設計」可以是撰寫最基礎的二進制0和1位元；也可以是建立在位元之上的<i>各類軟體語言</i>、演算法、架構、程式、圖像化程式碼來進行。</p>
</div>
