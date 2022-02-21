---
layout: page
title: Lead-Seq interactive
description: Explore the Lead-Seq data set.
img: assets/img/lead_seq_interactive.png
importance: 3
category: work
---

These plots illustrate data from Lead-Seq RNA structure probing on *Yersinia pseudotuberculosis* at 25°C and 37°C, published in [Twittenhoff, Brandenburg and Righetti et al., 2020](https://doi.org/10.1093/nar/gkaa404). To learn more about Lead-Seq and the data set, visit my [Lead-Seq project page]({{ site.baseurl }}{% link _projects/leadseq.md %}).

<br>

---

**How to use these plots:**
- **Enter a gene name** to select. *Currently only genes starting with 'TSS_6' are supported (e.g. TTS_61, TSS_646, TSS_688), more to come soon...*
- **Click on the lines** to highlight data.
-  **Scroll in** to get detailed views. *(Not available on mobile.)* 

---


  


<p ><div style="color:black !important;" id="observablehq-viewof-gene_select-e0b5238a"></div></p>
<div id="observablehq-viewof-panels-e0b5238a"></div>


<div id="observablehq-plot-e0b5238a"></div>


<script type="module">
import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
import define from "https://api.observablehq.com/d/5b50224d2147c93d.js?v=3";
new Runtime().module(define, name => {
  if (name === "plot") return new Inspector(document.querySelector("#observablehq-plot-e0b5238a"));
  if (name === "viewof panels") return new Inspector(document.querySelector("#observablehq-viewof-panels-e0b5238a"));
  if (name === "viewof gene_select") return new Inspector(document.querySelector("#observablehq-viewof-gene_select-e0b5238a"));
});
</script>


<br>

