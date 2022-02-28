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
-  **Scroll in** to get detailed views. <span style="font-size:10pt">*(not available on touchscreens)*</span> 
- **Toggle plot parts** to easily compare data. 

<br>





<center>
<span id="observablehq-textfield-93525b8f" ></span><span id="observablehq-button_update-93525b8f"></span>

<div style="font-size:10pt; margin-top:10px" id="observablehq-feedbacktext_search-93525b8f"></div>


<div   id="observablehq-plot-93525b8f"></div>

</center>

<div style="font-size:11pt; float: left">Toggle which plot panels you want to see:</div> <div style="font-size:11pt; float: right" id="observablehq-viewof-panels-93525b8f"></div> 

<br>

<br>

 <span style="float: right" id="observablehq-download_button-93525b8f"> </span>

<br>


**Annotated Features:**




<div id="observablehq-info_text-93525b8f"></div>



<br>

<br>

## Identification of RNA-Thermometers

This plot shows the Δscores and p-adjust values around the Shine-Dalgarno-Sequence (SDS). Transcripts with a negative Δscore and a very low p-adjust are considered good RNA-thermometer (RNAT) candidates. RNATs confirmed by [[1]: Twittenhoff, Brandenburg and Righetti et al., 2020](https://doi.org/10.1093/nar/gkaa404) are maked in orange, and those confirmed by [[2]: Righetti et al., 2016](https://doi.org/10.1073/pnas.1523004113) are marked in yellow.


<center>
<div style="margin-top:30px" id="observablehq-SDS_plot-93525b8f"></div>

</center>








<script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
import define from "https://api.observablehq.com/d/5b50224d2147c93d.js?v=3";
new Runtime().module(define, name => {
  if (name === "plot") return new Inspector(document.querySelector("#observablehq-plot-93525b8f"));
  if (name === "button_update") return new Inspector(document.querySelector("#observablehq-button_update-93525b8f"));
  if (name === "textfield") return new Inspector(document.querySelector("#observablehq-textfield-93525b8f"));
  if (name === "viewof panels") return new Inspector(document.querySelector("#observablehq-viewof-panels-93525b8f"));
  if (name === "feedbacktext_search") return new Inspector(document.querySelector("#observablehq-feedbacktext_search-93525b8f"));
  if (name === "download_button") return new Inspector(document.querySelector("#observablehq-download_button-93525b8f"));
  if (name === "info_text") return new Inspector(document.querySelector("#observablehq-info_text-93525b8f"));
  if (name === "SDS_plot") return new Inspector(document.querySelector("#observablehq-SDS_plot-93525b8f"));
});

document.getElementById("observablehq-textfield-93525b8f").style.display = "inline-block";

</script>