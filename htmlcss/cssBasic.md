# CSS 基本格式
所有的 html 標籤，都可以加上 class 或 id 屬性（使用 class 居多），再藉由 CSS 來以改變外觀。

```html
<style>
.名稱 {
    屬性1: 參數1;
    屬性2: 參數2;
}
</style>
```

## 基本格式
```html
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width,initial-scale=1">
        <title>我的網站</title>
        <style>
            .myTitle {
                color: #ffffff;
                background-color: blue;
            }
        </style>
    </head>
    <body>
        <h1 class="myTitle">第一個網頁內容</h1>
    </body>
</html>
```

<div style="border: 1px solid #ddd; padding: 30px; border-radius: 6px;">
<h1 class="myTitle" style="color: #fff;background-color: blue;">第一個網頁內容</h1>
</div>

<br />

- CSS 通常寫在 &lt;style> 裡面。
- “.” 對應的是 class。


## 常見屬性
|屬性|說明|示範參數|
|---|---|---|
|color|文字顏色|#ffffff
|background-color|背景顏色|#ff0000
|border|外框樣式|1px solid #ccc (粗細、線條樣式、顏色)|
|border-radius|圓角|1px
|font-size|文字大小|10pt
|font-weight|文字粗細|bold
|text-align|文字對齊|right
|margin|外距|15px|
|padding|內距|10px|