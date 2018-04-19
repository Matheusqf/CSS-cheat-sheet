# CSS-cheat-sheet


<code>Aligning contents Left and center with flexbox:
Add a third element on html:
<div class="parent">
  <div class="left">Left</div>
  <div class="center">Center</div>
  <div class="right"></div>
</div>

css:
.parent {
  display: flex;
}
.left, .right {
  flex: 1;
}</code>