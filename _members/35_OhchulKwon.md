---
layout: page
title: Ohchul Kwon
title_s1: Undergraduate Research Intern
title_s2: Seoul National University
description: dootheg0924 [at] snu.ac.kr
img: assets/img/okwon.png
importance: 35
category: current
---

### Short Bio
<p>Ohchul Kwon is a undergraduate research intern at the <a href="https://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
He is pursuing his B.S. in <a href="https://ie.snu.ac.kr/">Industrial Engineering </a>at the <a href="https://www.snu.ac.kr/">Seoul National University</a>.</p>

### Education
<ul>
<li>Undergraduate Research Intern, Seoul National University, 2025-present</li>
<li>B.S. Industrial Engineering, Seoul National University, 2021-present</li>
</ul>

### Employment History
<ul>
<li></li>
</ul>

For more information, visit Kwon's [personal website](https://dootheg0924.github.io/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
