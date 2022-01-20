---
layout: page
title: RNA thermometers
description: Detection of thermo-sensing RNA structures with Lead-Seq.
img: assets/img/thermometer_icon.png
importance: 3
category: work
---


RNA thermometers are temperature sensing structures, typically located at the 5'-end of RNAs. They impede translation at low temperatures by forming a stable secondary structure and blocking the ribosome binding site and the start codon. At high temperatures, they melt open, reveal the ribosome binding site, and the translation can take place.  

RNA thermometers can be identified with [Lead-Seq]({{ site.baseurl }}{% link _projects/2_leadseq.md %}), as shown in [Twittenhoff, Brandenburg and Righetti et al., 2020](https://doi.org/10.1093/nar/gkaa404).

&nbsp;


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/thermometer_icon_padded.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/thermometer_method_gross.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: RNA thermometer have different conformations at different temperatures. Right: Identification of RNA thermometers with Lead-Seq.  
</div>


To identify RNA thermometers from Lead-Seq data, Δscores are calculated from the distance between Lead-Scores at different temperatures. The Δscores around the ribosome binding site are compared to the Δscores of the whole transcript via Mann-Whitney-U test.

<!-- wiki link to mwu? -->

&nbsp;


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MWU3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rnat_experimental_validation.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption"> Left: Comparison of Δlead-scores and Mann-Whitney-U test for ribosome binding sites in <i>Yersinia pseudotuberculosis</i> as identified with Lead-Seq, including novel RNA thermometers (pink). Right: Experimental validation of the novel RNA themometers. 
</div>


The Δscores and p-values from the Mann-Whitney-U tests around ribosome binding sites in *Yersinia pseudotuberculosis* are compared. About 80 transcripts have a negative Δscore and a significant p-value (green), indicating significant melting at higher temperatures. These 80 transcripts are good candidates for RNA thermometers. Of these, 3 are verified RNA thermometers from [Righetti et al., 2016](https://doi.org/10.1073/pnas.1523004113) (purple), and 2 are previously unknown RNA thermometers, verified in [Twittenhoff, Brandenburg and Righetti et al., 2020](https://doi.org/10.1093/nar/gkaa404) (pink).
