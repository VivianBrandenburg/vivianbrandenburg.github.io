---
layout: page
title: Lead-Seq
description: Transcriptome-wide RNA structure probing with lead(II) ions.
img: assets/img/lead_icon.png
importance: 2
category: work
---

Lead-seq is a structure probing method for bacteria, which combines chemical structure probing with high-throughput sequencing. It allows for the probing of RNA structures of entire transcriptomes at different conditions. The method was first published by [Twittenhoff, Brandenburg and Righetti et al.](https://doi.org/10.1093/nar/gkaa404) in 2020, which was also reported in [ScienceDaily](https://www.sciencedaily.com/releases/2020/06/200617145959.htm). Code and Data for Lead-Seq are available in [GitHub](https://github.com/VivianBrandenburg/LeadSeq).

<!--  -->
<!-- todo: add git repo -->
<!--  -->

&nbsp;

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/lead_schematisch_breit.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Workflow of Lead-Seq. 
</div>



For Lead-Seq, a bacterial culture is treated with lead(II)-acetate. Lead(II) ions induce strand breaks in unpaired RNA regions. A second culture serves as negative control. Reverse Transcripase is added to both cultures, which creates a DNA copy of each RNA. In the lead-treated sample, the transcription stops when a lead-induced strand break is reached, whereas the transcription continues over this position in the control sample. Both samples are sequenced and mapped to the reference genome. The strand breaks are counted, and the normalized counts from both samples are used to calculate Lead-Scores. The Lead-Scores indicate single-stranded RNA regions. 

&nbsp;

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/l25_distribution.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/l37_distribution.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/performance_at_cut_05.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Lead-Scores of tRNAs at 25 °C (left) and 37 °C (middle). Selectivity and sensitivity for the same tRNAs (right).
</div>

Lead-Seq was tested on the γ-proteobacterium *Yersinia pseudotuberculosis* at 25 °C and 37 °C and validated with tRNA structures. At both temperatures, the Lead-Scores are significantly higher at unpaired than at paired regions. The selectivity above 0.7 shows that Lead-Scores indicate unpaired nucleotides at different testing conditions.  