---
layout: page
title: Chaeyoung Lee
title_s1: Undergraduate Research Intern
title_s2: Seoul National University
description: leecy0130 [at] snu.ac.kr
img: assets/img/clee.png
importance: 36
category: current
---

### Short Bio
<p>Chaeyoung Lee is a undergraduate research intern at the <a href="https://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
She is pursuing her B.S. in <a href="https://nursing.snu.ac.kr/">Nursing </a>at the <a href="https://www.snu.ac.kr/">Seoul National University</a>.</p>

### Education
<ul>
<li>B.S. Nursing, Seoul National University, 2019-present</li>
</ul>

### Employment History
<ul>
<li>Undergraduate Research Intern, HCAIL, Seoul National University, Seoul, Korea from 2025.</li>
</ul>

For more information, visit Lee's [personal website](https://its-chaeyounglee.github.io/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
