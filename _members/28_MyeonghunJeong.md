---
layout: page
title: Myeonghun Jeong
title_s1: Undergraduate Research Intern
title_s2: Seoul National University
description: jmhoon8 [at] snu.ac.kr
img: assets/img/mjeong.jpg
importance: 28
category: alumni
---

### Short Bio
<p>Myeonghun Jeong is an undergraduate research intern at the <a href="http://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
</p>

### Education
<ul>
<li>B.S. Nursing, Seoul National University 2024-present
</li>
<li>B.S. Energy Resources Engineering, Seoul National University, 2023
</li>
</ul>

### Employment History
<ul>
<li>Undergraduate Research Intern, HCAIL, Seoul National University, Seoul, Korea from December 2024.
</li>
</ul>

For more information, visit Jeong's [personal website](https://myeonghun-jeong.github.io/Myeonghun-jeong/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
