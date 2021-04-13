---
layout: page
title: "Tabs"
---

Content

<div class="nhs-tabs">
<input type="radio" name="tabs" id="tabone" checked="checked" />
<label for="tabone">Tab One</label>
<div class="tab">
<h3>Tab One Content</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
</div>
<input type="radio" name="tabs" id="tabtwo" />
<label for="tabtwo">Tab Two</label>
<div class="tab">
<h3>Tab Two Content</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
</div>
 
<input type="radio" name="tabs" id="tabthree" />
<label for="tabthree">Tab Three</label>
<div class="tab">
<h3>Tab Three Content</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
</div>
</div>

<div id="code">
&lt;div class="nhs-tabs"&gt;<br>
&nbsp; &lt;input type="radio" name="tabs" id="tabone"
checked="checked" /&gt;<br>
&nbsp; &lt;label for="tabone"&gt;Tab
One&lt;/label&gt;<br>
&nbsp; &lt;div class="tab"&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;h3&gt;Tab One
Content&lt;/h3&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;p&gt;Lorem ipsum dolor sit
amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut
labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est
laborum.&lt;/p&gt;<br>
&nbsp; &lt;/div&gt;<br>
&nbsp; &lt;input type="radio" name="tabs" id="tabtwo" /&gt;<br>
&nbsp; &lt;label for="tabtwo"&gt;Tab
Two&lt;/label&gt;<br>
&nbsp; &lt;div class="tab"&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;h3&gt;Tab Two
Content&lt;/h3&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;p&gt;Lorem ipsum dolor sit
amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut
labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est
laborum.&lt;/p&gt;<br>
&nbsp; &lt;/div&gt;<br>
<br>
&nbsp; &lt;input type="radio" name="tabs" id="tabthree"
/&gt;<br>
&nbsp; &lt;label for="tabthree"&gt;Tab
Three&lt;/label&gt;<br>
&nbsp; &lt;div class="tab"&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;h3&gt;Tab Three
Content&lt;/h3&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;p&gt;Lorem ipsum dolor sit
amet, consectetur adipisicing elit.&lt;/p&gt;<br>
&nbsp; &lt;/div&gt;<br>
&lt;/div&gt;<br>

</div>

<script>
window.onload = function() {
  document.getElementById('/components/tabs').className = 'nhs-fancy2';
};
</script>
