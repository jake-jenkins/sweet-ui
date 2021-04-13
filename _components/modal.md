---
layout: page
title: "Modal"
---

Content

<details>
        <summary>
          <div class="nhs-btn nhs-fancy2">
            Open Modal
          </div>
          <div class="nhs-modal-overlay"></div>
        </summary>
        <div class="nhs-modal">
          <div class="nhs-modal-close">
              <svg xmlns="http://www.w3.org/2000/svg" height="24px" viewBox="0 0 24 24" width="24px" fill="#000000"><path d="M0 0h24v24H0V0z" fill="none"/><path d="M19 6.41L17.59 5 12 10.59 6.41 5 5 6.41 10.59 12 5 17.59 6.41 19 12 13.41 17.59 19 19 17.59 13.41 12 19 6.41z"/></svg>
          </div>
          <div class="nhs-modal-title">
            <h1>My details modal</h1>
          </div>
          <div class="nhs-modal-content">
            <p>
              You can click the X in the corner or click the overlay to close this modal.
              Something like this could be useful as a nice way to show additional information,
              but that's about as far as I would take it. It's just a nice way of styling the details element.
            </p>
          </div>
        </div>
      </details>

<div id="code">
&lt;details&gt;<br>
&nbsp; &lt;summary&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;div class="nhs-btn
nhs-fancy2"&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Open Modal<br>
&nbsp;&nbsp;&nbsp; &lt;/div&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;div
class="nhs-modal-overlay"&gt;&lt;/div&gt;<br>
&nbsp; &lt;/summary&gt;<br>
&nbsp; &lt;div class="nhs-modal"&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;div
class="nhs-modal-close"&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;svg
xmlns="http://www.w3.org/2000/svg" height="24px" viewBox="0 0 24 24"
width="24px" fill="#000000"&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;path d="M0 0h24v24H0V0z" fill="none" /&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;path d="M19 6.41L17.59 5 12 10.59 6.41 5 5 6.41 10.59 12 5
17.59 6.41 19 12 13.41 17.59 19 19 17.59 13.41 12 19 6.41z" /&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;/svg&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;/div&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;div
class="nhs-modal-title"&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;h1&gt;My
details modal&lt;/h1&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;/div&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;div
class="nhs-modal-content"&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;p&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
You can click the X in the corner or click the overlay to close this
modal.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Something like this could be useful as a nice way to show additional
information,<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
but that's about as far as I would take it. It's just a nice way of
styling the details element.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;/p&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;/div&gt;<br>
&nbsp; &lt;/div&gt;<br>
&lt;/details&gt;


</div>

<script>
window.onload = function() {
  document.getElementById('/components/modal').className = 'nhs-fancy2';
};
</script>
