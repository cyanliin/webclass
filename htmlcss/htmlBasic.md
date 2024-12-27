# HTML 基本格式
網站用來標記結構的文字格式。當檔案存擋為 .html 文件時，瀏覽器就會以 HTML 的格式去算圖（render）出網頁的畫面。

## 格式說明

格式
```xml
<標籤>(內容)</標籤>

ex:
<h1>我是標題</h1>
```

巢狀結構（可以層層包下去）
```xml
<標籤a>
    <標籤b>
        <標籤c>內容</標籤c>
    </標籤b>
</標籤a>

```

## 最基本的 HTML 結構
以下是最基本的網頁 HTML。

```html
<html>
    <head>
        <title>我的網站</title>
    </head>
    <body>
        <h1>第一個網頁內容</h1>
    </body>
</html>
```

|標籤|說明|
|---|---|
|&lt;html>|HTML開始。|
|&lt;head>|放該網頁的相關設定。|
|&lt;body>|放該網頁的實際內容。|
|&lt;title>|網站的標題（於視窗列）|
|&lt;h1>|內文標題1|

:::tip 標籤慣例都使用小寫
雖然大小寫都可以，但當前業界慣例是統一使用小寫。
:::

<br />

## &lt;head> 裡的必備設定


### 1. 設定編碼為 utf-8
避免比較舊的瀏覽器出現亂碼。
```html
<meta charset="utf-8">
```

### 2. 設定手機檢視大小
避免手機瀏覽器預設會把全頁面縮小顯示，而導致文字過小難以閱讀。所以設定初始縮放為1。
```html
<meta name="viewport" content="width=device-width,initial-scale=1">
```

## 完整的基本結構
```html
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width,initial-scale=1">
        <title>我的網站</title>
    </head>
    <body>
        <h1>第一個網頁內容</h1>
    </body>
</html>
```