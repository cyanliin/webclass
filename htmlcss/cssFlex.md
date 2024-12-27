# CSS 排版-Flex

## 靠左對齊
```html
<div class="layout">
    <div class="item">item1</div>
    <div class="item">item2</div>
    <div class="item">item3</div>
    <div class="item">item4</div>
</div>
```
```css
.layout {
    display: flex;
    justify-content: start;
    gap: 10px;
}

.item {
    background-color: orange;
}
```
<div style="border: 1px solid #ddd; padding: 30px; border-radius: 6px;">
    <div style="display: flex; justify-content: start; gap: 10px;">
        <div style="background-color: orange;">item1</div>
        <div style="background-color: orange;">item2</div>
        <div style="background-color: orange;">item3</div>
        <div style="background-color: orange;">item4</div>
    </div>
</div>

## 往兩邊靠
```html
<div class="layout">
    <div class="item">Left</div>
    <div class="item">Right</div>
</div>
```
```css
.layout {
    display: flex;
    justify-content: space-between;
}

.item {
    background-color: orange;
}
```
<div style="border: 1px solid #ddd; padding: 30px; border-radius: 6px;">
    <div style="display: flex;justify-content: space-between;">
        <div style="background-color: orange;">Left</div>
        <div style="background-color: orange;">Right</div>
    </div>
</div>