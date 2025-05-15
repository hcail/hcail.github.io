---
layout: page
title: Minh Do Ngoc Luong
title_s1: Research Intern
title_s2: Seoul National University
description: ngminglgdo [at] snu.ac.kr
img: assets/img/mluong.png
importance: 34
category: current
---

### Short Bio
<p>Minh Do Ngoc Luong is a research intern at the <a href="https://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
She received her B.S. in <a href="https://cse.snu.ac.kr/">Computer Science and Engineering </a>at the <a href="https://www.snu.ac.kr/">Seoul National University</a> in 2025.</p>

### Education
<ul>
<li>B.S. Computer Science and Engineering, Seoul National University, 2019-2025</li>
</ul>

### Employment History
<ul>
<li>Research Intern, HCAIL, Seoul National University, Seoul, Korea from May 2025</li>
</ul>

For more information, visit Luong's [personal website](https://minhlgdo.com/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
