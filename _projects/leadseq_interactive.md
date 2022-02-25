---
layout: page
title: Lead-Seq interactive
description: Explore the Lead-Seq data set.
img: assets/img/lead_seq_interactive.png
importance: 3
category: work
---

These plots illustrate data from Lead-Seq RNA structure probing on *Yersinia pseudotuberculosis* at 25°C and 37°C, published in [Twittenhoff, Brandenburg and Righetti et al., 2020](https://doi.org/10.1093/nar/gkaa404). To learn more about Lead-Seq and the data set, visit my [Lead-Seq project page]({{ site.baseurl }}{% link _projects/leadseq.md %}).  

On this page, you can...

- **Enter a transcript name** to change the data displayed data.
- **Click on the lines** to highlight.
-  **Scroll in** to get detailed views. <span style="font-size:10pt">*(not available on touchscreens)*</span> 
- **Toggle plot parts** to easily compare data. 

<br>





<center>
<span id="observablehq-textfield-3eba64a4" ></span><span id="observablehq-button_update-3eba64a4"></span>

<div style="font-size:10pt; margin-top:10px" id="observablehq-feedbacktext_search-3eba64a4"></div>


<span id="observablehq-plot-3eba64a4"></span>
<br>
<span style="font-size:11pt" id="observablehq-viewof-panels-3eba64a4"></span> 

</center>



<span style="float: right" id="observablehq-download_button-3eba64a4"> </span>

<br>

---

<br>


**Annotated Features:**




<div id="observablehq-info_text-3eba64a4"></div>





<script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
import define from "https://api.observablehq.com/d/5b50224d2147c93d.js?v=3";
new Runtime().module(define, name => {
  if (name === "plot") return new Inspector(document.querySelector("#observablehq-plot-3eba64a4"));
  if (name === "textfield") return new Inspector(document.querySelector("#observablehq-textfield-3eba64a4"));
  if (name === "button_update") return new Inspector(document.querySelector("#observablehq-button_update-3eba64a4"));
  if (name === "viewof panels") return new Inspector(document.querySelector("#observablehq-viewof-panels-3eba64a4"));
  if (name === "feedbacktext_search") return new Inspector(document.querySelector("#observablehq-feedbacktext_search-3eba64a4"));
  if (name === "download_button") return new Inspector(document.querySelector("#observablehq-download_button-3eba64a4"));
  if (name === "info_text") return new Inspector(document.querySelector("#observablehq-info_text-3eba64a4"));
});



document.getElementById("observablehq-textfield-3eba64a4").style.display = "inline-block";


</script>
