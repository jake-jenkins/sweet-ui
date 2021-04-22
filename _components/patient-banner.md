---
layout: page
title: "Patient Banner"
---

Patient banner shows the active patient selected in the system.

<div class="pt-banner">
        <div id="pt-name">Jake Testerson</div>
        <div id="pt-crn">Male<br />
            15/03/1984 (37)
        </div>
        <div id="pt-nhs">NHS: 999-999-9999<br />
        CRN: 12345678
        </div>
        <div id="pt-alerts">
            <span class="nhs-tag nhs-light-grey">Inpatient</span>
            <span class="nhs-tag nhs-red">
                <i class="fas fa-exclamation"></i> Click for Alerts</span>
        </div> 
    </div> 
    
  <div class="pt-banner-ext">
        <div class="nhs-grid">
            <div id="pt-ext1">
                <h4>Alerts</h4>
                <ul class="nhs-text-red">
                    <li>Smoker</li>
                    <li>Diabetes</li>
                    <li>Fabulous</li>
                </ul>
            </div>
            <div id="pt-ext2">
                <h4>Contact</h4>
                <i class="fas fa-phone-alt"></i> 07444 444 444
                <h5>Address</h5>
                4 Abbots Close<br />
                Fleet<br />
                GU51 3RF
            </div>
  <div id="pt-ext3">
                <h4>Next of Kin</h4>
                <p>
                Name: Nick Testerson<br/>
                Relationship: Partner<br />
                </p>
                <h5>Address</h5>
                4 Abbots Close<br />
                Fleet<br />
                GU51 3RF
            </div>
  <div id="pt-ext4">
                <h4>GP</h4>
                Best Test GP Surgery<br />
                <i class="fas fa-phone-alt"></i> 02920 202020
                <h5>Address</h5>
                5 Strathy Rd<br /> 
                St. Mellons<br />
                Cardiff<br />
                CF3 0SH
            </div>
        </div>
    </div>

<script>
            var acc = document.getElementsByClassName("pt-banner");
            var i;
            
            for (i = 0; i < acc.length; i++) {
              acc[i].addEventListener("click", function() {
                var panel = this.nextElementSibling;
                if (panel.style.display === "block") {
                  panel.style.display = "none";
                } else {
                  panel.style.display = "block";
                }
              });
            }
            </script>

<div id="code">
&lt;div class="pt-banner"&gt;<br>
&nbsp; &lt;div id="pt-name"&gt;Jake
Testerson&lt;/div&gt;<br>
&nbsp; &lt;div id="pt-crn"&gt;Male&lt;br /&gt;<br>
&nbsp;&nbsp;&nbsp; 15/03/1984 (37)<br>
&nbsp; &lt;/div&gt;<br>
&nbsp; &lt;div id="pt-nhs"&gt;NHS: 999-999-9999&lt;br
/&gt;<br>
&nbsp;&nbsp;&nbsp; CRN: 12345678<br>
&nbsp; &lt;/div&gt;<br>
&nbsp; &lt;div id="pt-alerts"&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;span class="nhs-tag
nhs-light-grey"&gt;Inpatient&lt;/span&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;span class="nhs-tag
nhs-red"&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;i class="fas
fa-exclamation"&gt;&lt;/i&gt; Click for
Alerts&lt;/span&gt;<br>
&nbsp; &lt;/div&gt;<br>
&lt;/div&gt;<br>
<br>
&lt;div class="pt-banner-ext"&gt;<br>
&nbsp; &lt;div class="nhs-grid"&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;div id="pt-ext1"&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;h4&gt;Alerts&lt;/h4&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;ul class="nhs-text-red"&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;li&gt;Smoker&lt;/li&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;li&gt;Diabetes&lt;/li&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;li&gt;Fabulous&lt;/li&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;/ul&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;/div&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;div id="pt-ext2"&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;h4&gt;Contact&lt;/h4&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;i class="fas
fa-phone-alt"&gt;&lt;/i&gt; 07444 444 444<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;h5&gt;Address&lt;/h5&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 4 Abbots
Close&lt;br /&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Fleet&lt;br
/&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; GU51 3RF<br>
&nbsp;&nbsp;&nbsp; &lt;/div&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;div id="pt-ext3"&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;h4&gt;Next of Kin&lt;/h4&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;p&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Name: Nick Testerson&lt;br /&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Relationship: Partner&lt;br /&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;/p&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;h5&gt;Address&lt;/h5&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 4 Abbots
Close&lt;br /&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Fleet&lt;br
/&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; GU51 3RF<br>
&nbsp;&nbsp;&nbsp; &lt;/div&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;div id="pt-ext4"&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;h4&gt;GP&lt;/h4&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Best Test GP
Surgery&lt;br /&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;i class="fas
fa-phone-alt"&gt;&lt;/i&gt; 02920 202020<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&lt;h5&gt;Address&lt;/h5&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 5 Strathy
Rd&lt;br /&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; St.
Mellons&lt;br /&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Cardiff&lt;br
/&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; CF3 0SH<br>
&nbsp;&nbsp;&nbsp; &lt;/div&gt;<br>
&nbsp; &lt;/div&gt;<br>
&lt;/div&gt;<br>
<br>
&lt;script&gt;<br>
&nbsp; var acc = document.getElementsByClassName("pt-banner");<br>
&nbsp; var i;<br>
<br>
&nbsp; for (i = 0; i &lt; acc.length; i++) {<br>
&nbsp;&nbsp;&nbsp; acc[i].addEventListener("click",
function() {<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; var panel =
this.nextElementSibling;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; if
(panel.style.display === "block") {<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
panel.style.display = "none";<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; } else {<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
panel.style.display = "block";<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }<br>
&nbsp;&nbsp;&nbsp; });<br>
&nbsp; }<br>
&lt;/script&gt;

</div>

<script>
window.onload = function() {
  document.getElementById('/components/patient-banner').className = 'nhs-fancy2';
};
</script>
