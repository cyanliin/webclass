# HTML 清單

## UL 無序號清單
```html
<ul>
    <li>項目1</li>
    <li>項目2</li>
    <li>項目3</li>
</ul>
```

<div style="border: 1px solid #ddd; padding: 30px; border-radius: 6px;">
<ul>
    <li>項目1</li>
    <li>項目2</li>
    <li>項目3</li>
</ul>
</div>

## OL 有序號清單
```html
<ol>
    <li>項目1</li>
    <li>項目2</li>
    <li>項目3</li>
</ol>
```

<div style="border: 1px solid #ddd; padding: 30px; border-radius: 6px;">
<ol>
    <li>項目1</li>
    <li>項目2</li>
    <li>項目3</li>
</ol>
</div>

## 巢狀結構（嵌套）
```html
<ul>
    <li>項目1</li>
    <li>
        <ul>
            <li>項目2-1</li>
            <li>項目2-2</li>
            <li>項目2-3</li>
        </ul>
    </li>
    <li>項目3</li>
</ul>
```

<div style="border: 1px solid #ddd; padding: 30px; border-radius: 6px;">
<ul>
    <li>項目1</li>
    <li>項目2：
        <ul>
            <li>項目2-1</li>
            <li>項目2-2</li>
            <li>項目2-3</li>
        </ul>
    </li>
    <li>項目3：
        <ol>
            <li>項目3-1</li>
            <li>項目3-2</li>
            <li>項目3-3</li>
        </ol>
    </li>
</ul>
</div>