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

- **enter a gene or transcript name** to change the data displayed data 
  <span style="font-size:10pt">*(Currently only transcripts starting with 'TSS_6' are supported (e.g. TTS_61, TSS_646, TSS_688), more to come soon...)*</span> 
- **click on the lines** to highlight
-  **scroll in** to get detailed views <span style="font-size:10pt">*(not available on touchscreens)*</span> 
- **toggle plot parts** to easily compare data 

<br>




<center> 
<span id="observablehq-field_text-b986972f"></span>
<span id="observablehq-button_update-b986972f"></span>
<span id="observablehq-plot-b986972f"></span>
<br>
<span style="font-size:11pt" id="observablehq-viewof-panels-b986972f"></span> 
 </center>



<span style="float: right" id="observablehq-download_button-b986972f"> </span>

<br>

---

<br>


**Annotated Features:**

<div id="observablehq-info_text-b986972f"></div>



<script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
import define from "https://api.observablehq.com/d/5b50224d2147c93d.js?v=3";
new Runtime().module(define, name => {
  if (name === "plot") return new Inspector(document.querySelector("#observablehq-plot-b986972f"));
  if (name === "button_update") return new Inspector(document.querySelector("#observablehq-button_update-b986972f"));
  if (name === "viewof panels") return new Inspector(document.querySelector("#observablehq-viewof-panels-b986972f"));
  if (name === "field_text") return new Inspector(document.querySelector("#observablehq-field_text-b986972f"));
  if (name === "download_button") return new Inspector(document.querySelector("#observablehq-download_button-b986972f"));
  if (name === "info_text") return new Inspector(document.querySelector("#observablehq-info_text-b986972f"));
});
</script>


