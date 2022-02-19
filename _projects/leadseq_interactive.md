---
layout: page
title: Lead-Seq interactive
description: Explore the Lead-Seq data set.
img: assets/img/lead_seq_interactive.png
importance: 3
category: work
---


Simply enter a gene name to display the data, and zoom into the plots to get detailed views. Select which data are shown via the checkboxes, and highlight data by clicking on the legend.  
<i> Currently only genes starting with 'TSS_6' are supported. More to come soon... </i>

<br>
<div id="observablehq-viewof-gene_select-e0b5238a"></div>
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

To learn more about Lead-Seq, visit my [Lead-Seq project page]({{ site.baseurl }}{% link _projects/leadseq.md %}).