---
layout: page
title: Duhyung Kwak
title_s1: Undergraduate Research Intern
title_s2: Seoul National University
description: rvanpersie20 [at] snu.ac.kr
img: assets/img/dkwak.png
importance: 29
category: current
---

### Short Bio
<p>Duhyung Kwak is an undergraduate research intern at the <a href="http://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
</p>

### Education
<ul>
<li>B.S. Nursing, Seoul National University 2019-present.
</li>
</ul>

### Employment History
<ul>
<li>Undergraduate Research Intern, HCAIL, Seoul National University, Seoul, Korea from December 2024.
</li>
</ul>

For more information, visit Kwak's [personal website](https://duhyung.framer.website/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>