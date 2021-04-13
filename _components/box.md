---
layout: page
title: "Box"
---

A box used to display key information on a page.

Box Title

<div class="nhs-box">
<div class="nhs-box-header">Box Title</div>
<p>Box Text</p>
</div>

<div id="code">
&lt;div class="nhs-box"&gt;<br>
&nbsp; &lt;div class="nhs-box-header"&gt;Box
Title&lt;/div&gt;<br>
&nbsp; &lt;p&gt;Box Text&lt;/p&gt;<br>
&lt;/div&gt;
</div>

<div class="nhs-box nhs-light-green">
<div class="nhs-box-header nhs-green">Box Title</div>
<p>Box Text</p>
</div>

<div id="code">
&lt;div class="nhs-box nhs-light-green"&gt;<br>
&nbsp; &lt;div class="nhs-box-header nhs-green"&gt;Box
Title&lt;/div&gt;<br>
&nbsp; &lt;p&gt;Box Text&lt;/p&gt;<br>
&lt;/div&gt;
</div>

<div class="nhs-box nhs-light-yellow">
<div class="nhs-box-header nhs-yellow">Box Title</div>
<p>Box Text</p>
</div>

<div id="code">
&lt;div class="nhs-box nhs-light-yellow"&gt;<br>
&nbsp; &lt;div class="nhs-box-header nhs-yellow"&gt;Box
Title&lt;/div&gt;<br>
&nbsp; &lt;p&gt;Box Text&lt;/p&gt;<br>
&lt;/div&gt;
</div>

<script>
window.onload = function() {
  document.getElementById('/components/box').className = 'nhs-fancy2';
};
</script>
