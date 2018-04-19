# CSS-cheat-sheet


Add a third element on html:
Aligning contents Left and center with flexbox:
```html
<div class="parent">
  <div class="left">Left</div>
  <div class="center">Center</div>
  <div class="right"></div>
</div>
```

<code>.parent {
  display: flex;
}
.left, .right {
  flex: 1;
}</code>
