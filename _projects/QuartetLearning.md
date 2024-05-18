---
layout: page
title: Quartet Learning
description: Infer phylogenetic features from almost arbitrary data types
img: assets/img/quartet_learning/quartet_learning_icon.png
importance: 1
category: work
---



Quartet Learning uses state-of-the art deep learning to infer phylogenetically informative features from almost arbitrary data types. 


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/quartet_learning/quartet_learning_overview.png" title="quartet learning overview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview over Quartet Learning
</div>

The input is organized in quartets along a phylogenetic tree. The model produces an output vector for each input, that can be interpreted as the expression level of a designated set of features. The feature vectors of each input quartet are used to calculate a split tree. The loss function then minimizes the edge of the split that is not present in the phylogenetic tree. 





<div class="row">
    <div class="col-sm mt-1 mt-md-0">
        {% include figure.html path="assets/img/quartet_learning/quartet_learning_results.png" title="quartet learning results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Quartet Leanring reproduces reference trees by infering phylogenetic features
</div>



