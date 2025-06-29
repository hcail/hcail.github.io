---
layout: page
title: Seungjun Chong
title_s1: Undergraduate Research Intern
title_s2: University of Wisconsin–Madison
description: jchong990315 [at] gmail.com
img: assets/img/schong.png
importance: 38
category: current
---

### Short Bio
<p>Seungjun Chong is a undergraduate research intern at the <a href="https://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
He is pursuing his B.S. in <a href="https://www.cs.wisc.edu/">Computer Science </a>at the <a href="https://www.wisc.edu/">University of Wisconsin - Madison</a>.</p>

### Education
<ul>
<li>B.S. Computer Science, University of Wisconsin–Madison, 2019-present</li>
</ul>

### Employment History
<ul>
<li>Undergraduate Research Intern, HCAIL, Seoul National University, Seoul, Korea from 2025.</li>
<li>Undergraduate Research Intern, WiNGS Lab, University of Wisconsin–Madison, WI, USA from 2024 to 2025.</li>
<li>Software Engineer, THEARHAN, Seoul, Korea from 2019 to 2021.</li>
</ul>

For more information, visit Chong's [personal website](https://chong-portfolio.vercel.app/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
