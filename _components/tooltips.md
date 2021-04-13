---
layout: page
title: "Tooltips"
---

<div class="nhs-tooltip">
  <a href="#" class="nhs-btn nhs-fancy2">Hover over me!</a>
    <span class="nhs-tooltiptext">
    Tooltip text
    </span>
</div>

<div id="code">
&lt;div class="nhs-tooltip"&gt;<br>
&nbsp; &lt;a href="#" class="nhs-btn nhs-fancy2"&gt;Hover
over me!&lt;/a&gt;<br>
&nbsp; &lt;span class="nhs-tooltiptext"&gt;<br>
&nbsp;&nbsp;&nbsp; Tooltip text<br>
&nbsp; &lt;/span&gt;<br>
&lt;/div&gt;

</div>
<script>
window.onload = function() {
  document.getElementById('/components/tooltips').className = 'nhs-fancy2';
};
</script>
