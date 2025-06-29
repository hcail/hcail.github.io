---
layout: page
title: Hyeonmin Choi
title_s1: Undergraduate Research Intern
title_s2: Seoul National University
description: alexfamily28 [at] snu.ac.kr
img: assets/img/hchoi.png
importance: 37
category: current
---

### Short Bio
<p>Hyeonmin Choi is an undergraduate research intern at the <a href="https://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
He is pursuing his B.S. in <a href="https://ece.snu.ac.kr/">Electrical and Computer Engineering </a>at <a href="https://www.snu.ac.kr/">Seoul National University</a>.</p>

### Education
<ul>
<li>Electrical and Computer Engineering, Seoul National University, 2024-present</li>
</ul>

### Employment History
<ul>
<li>Undergraduate Research Intern, HCAIL, Seoul National University, Seoul, Korea from 2025.</li>
</ul>

For more information, visit Choi's [personal website](https://hyunminchoi.my.canva.site/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
</div>
