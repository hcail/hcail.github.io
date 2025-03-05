---
layout: page
title: Jihyeon Park
title_s1: Research Intern
title_s2: Cha University
description: jp883 [at] cornell.edu
img: assets/img/jpark.png
importance: 30
category: current
---

### Short Bio
<p>Jihyeon Park is a research intern at the <a href="http://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
</p>

### Education
<ul>
<li>M.D. Candidate, Cha University School of Medicine Mar. 2023-Present.
</li>
<li>B.S. with Distinction, Human Ecology, Cornell University Aug. 2019 to May 2022.
</li>
</ul>

### Employment History
<ul>
<li>Research Intern, HCAIL, Seoul, Korea from Mar. 2025.</li>
<li>Undergraduate Research Intern, Microbiology Lab, Jeju, Korea from Sep. 2023 to Dec. 2023.</li>
<li>Undergraduate Research Intern, Child Witness and Cognition Lab, Ithaca, NY, USA from Sep. 2020 to May 2022.</li>
<li>Undergraduate Research Intern, HCAIL, Seoul, Korea from Jun. 2020 to May 2021.</li>
</ul>

For more information, visit Park's [personal website](https://jihyeonpark.super.site/).
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
