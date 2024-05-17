---
layout: page
permalink: /CV_academic/
title: cv
description: <b>Curriculum Vitæ of Vivian Brandenburg</b>
nav: false
nav_order: 4
years_talks: [2023, 2022, 2021, 2020]
years_posters: [2023, 2021, 2020]
years: [2024, 2023, 2022, 2021, 2020, 2019]
---

### Professional Experience
---

| &emsp;    &emsp;  &emsp;  &emsp;  &emsp;  &emsp; &emsp; &thinsp; | &emsp;                                                                   |
| ------------------------------------------------------- | ------------------------------------------------------------------------ |
| since 2023                                              | **Postdoctoral Researcher**, Ruhr University Bochum                      |
|                                                         | Bioinformatics Group                                                     |
|                                                         |                                                                          |
| 2019 -- 2023                                            | **Doctoral Researcher**, Ruhr University Bochum                          |
|                                                         | Research Groups: Microbial Biology \| Bioinformatics                     |
|                                                         |                                                                          |
| 2018 -- 2019                                            | **Teaching Assistant**, Ruhr University Bochum                           |
|                                                         | Research Group: Theoretical Computer Science                             |
|                                                         |                                                                          |
| 2014                                                    | **Teaching Assistant**, Leipzig University                               |
|                                                         | Research Group: Plant Physiology                                         |
|                                                         |                                                                          |
| 2014                                                    | **Research Intern**, Helmholtz Center for Environmental Research Leipzig |
|                                                         | Research Group: Science-Policy-Interface                                 |

<br>



### Education
---

| &emsp;    &emsp;  &emsp;  &emsp;  &emsp;  &emsp; &emsp; | &emsp;                                                                                                                  |
| ------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| 2023                                                    | **Doctoral Degree**, Ruhr University Bochum                                                                             |
|                                                         | Thesis: *Investigation of functional RNA structures using deep learning and experiment-guided computational approaches* |
|                                                         |                                                                                                                         |
| 2017 -- 2019                                            | **M.Sc. Biology**, Ruhr University Bochum                                                                               |
|                                                         | Master Thesis: *Systematic Comparison of RNA Structure Probing Data.*                                                   |
|                                                         |                                                                                                                         |
| 2014 -- 2017                                            | **M.Sc. Biology**, Martin Luther University Halle-Wittenberg                                                            |
|                                                         | Specialization in Crops Science                                                                                         |
|                                                         |                                          |                                                                                                                         |
| 2011 -- 2014                                            | **B.Sc. Biology** , Leipzig University                                                                                  |
|                                                         | Bachelor Thesis: *Study of the Nitrogen Acquisition of the Wheat Variety ’Akteur’.*                                     |

<br>


### Publications

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography --file papers --query @*[year={{y}}]* %}
{% endfor %}

</div>

<br>

### Talks
<div class="publications">

{% for y in page.years_talks %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f talks -q @*[year={{y}}]* %}
{% endfor %}

</div>


&nbsp;

&nbsp;


### Posters

<div class="publications">

{% for y in page.years_posters %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f posters -q @*[year={{y}}]* %}
{% endfor %}

</div>



### Teaching
---                        



|   &emsp;    &emsp;  &emsp;  &emsp;  &emsp;  &emsp; &emsp; &thinsp;| &emsp;                                                                                                       |
| ------------ | ------------------------------------------------------------------------------------------------------------ |
| since 2023   | **Big Data in Bioinformatics**                                                                               |
|              | Supervision of student's projects                                                                            |
|              | *Ruhr University Bochum, Bioinformatics*                                                                     |
|              |                                                                                                              |
| since 2022   | **Literature Seminar Bioinformatics**                                                                        |
|              | Supervision of master students talks                                                                         |
|              | *Ruhr University Bochum, Bioinformatics*                                                                     |
|              |                                                                                                              |
| since 2019   | **Module Bioinformatics**                                                                                    |
|              | Supervision of course days 'RNA structure prediction' & 'Analysis of genome-wide RNA structure probing data' |
|              | *Ruhr University Bochum, Bioinformatics*                                                                     |
|              |                                                                                                              |
| since 2019   | **Module Microbiology and Biotechnology**                                                                    |
|              | Supervision of course part 'Bioinformatics'                                                                  |
|              | *Ruhr University Bochum, Microbial Biology*                                                                  |
|              |                                                                                                              |
| 2018 -- 2019 | **Database Systems**                                                                                         |
|              | Evaluation of weekly exercises                                                                               |
|              | *Ruhr University Bochum, Theoretical Computer Science*                                                       |
|              |                                                                                                              |
| 2014         | **Plant Physiology**                                                                                         |
|              | Teaching assistance in practical course                                                                      |
|              | *Leipzig University, Plant Physiology*                                                                       |
|              |                                                                                                              |

