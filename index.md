---
layout: home
title: "Home"
---

<div class="nhs-hero nhs-fancy">
<h1>UI Components for NHS Apps</h1>
</div>
<h1 class="fancy-text">Introduction</h1>

sweet.ui components have been crafted to add consistent, clean design to apps and websites. It can be used on it's own, or in addition to another framework, eg bootstrap.

---

<h2 class="fancy-text">Get Started</h2>

Adding sweet.ui Components to an app or site is simple by adding some lines into your template file.

1. Add script snippets below.
2. Start adding classes to your code to use components.
   <br />

#### Add inside &lt;head&gt; tag

<div id="code">
<p>&lt;link rel="stylesheet" href="https://sweet.pages.dev/css/components.css"&gt;<br />&lt;link rel="stylesheet" href="https://sweet.pages.dev/css/colours.css"&gt;<br />&lt;link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" /&gt;</p>
</div>

#### Add above &lt;/body&gt; tag

<div id="code">
<p>&lt;script src="https://sweet.pages.dev/js/scripts.js"&gt;&lt;/script&gt;</p>
</div>

<script>
window.onload = function() {
  document.getElementById('intro').className = 'nhs-fancy2';
};
</script>
