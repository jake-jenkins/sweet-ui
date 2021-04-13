---
layout: page
title: "Menu"
---

Content

<nav class="nhs-h-menu">
<a href="#">Item 1</a>
<div class="nhs-dropdown">
<span>Item 2</span>
  <div class="nhs-dropdown-content">
    <a href="#">Item 2a</a>
    <a href="#">Item 2b</a>
    <a href="#">Item 2c</a>
  </div>
</div>
<a href="#">Item 3</a>
<div class="nhs-dropdown">
<span>Item 4</span>
  <div class="nhs-dropdown-content">
    <a href="#">Item 4a</a>
    <a href="#">Item 4b</a>
    <a href="#">Item 4c</a>
  </div>
</div>
<a href="#">Item 5</a>
</nav>

<div id="code">
&lt;nav class="nhs-h-menu"&gt;<br>
&nbsp; &lt;a href="#"&gt;Item 1&lt;/a&gt;<br>
&nbsp; &lt;div class="nhs-dropdown"&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;span&gt;Item
2&lt;/span&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;div
class="nhs-dropdown-content"&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;a
href="#"&gt;Item 2a&lt;/a&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;a
href="#"&gt;Item 2b&lt;/a&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;a
href="#"&gt;Item 2c&lt;/a&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;/div&gt;<br>
&nbsp; &lt;/div&gt;<br>
&nbsp; &lt;a href="#"&gt;Item 3&lt;/a&gt;<br>
&nbsp; &lt;div class="nhs-dropdown"&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;span&gt;Item
4&lt;/span&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;div
class="nhs-dropdown-content"&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;a
href="#"&gt;Item 4a&lt;/a&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;a
href="#"&gt;Item 4b&lt;/a&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;a
href="#"&gt;Item 4c&lt;/a&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;/div&gt;<br>
&nbsp; &lt;/div&gt;<br>
&nbsp; &lt;a href="#"&gt;Item 5&lt;/a&gt;<br>
&lt;/nav&gt;

</div>

<script>
window.onload = function() {
  document.getElementById('/components/menu').className = 'nhs-fancy2';
};
</script>
