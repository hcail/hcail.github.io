---
layout: page
title: Jisu Son
title_s1: M.S. Student
title_s2: Seoul National University
description: blanksoo15 [at] gmail.com
img: assets/img/jsson.png
importance: 33
category: current
---

### Short Bio
<p>Jisu Son is an M.S. student at the <a href="https://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
</p>

### Education
<ul>
<li>M.S. Nursing Informatics, Seoul National University, 2025-present</li>
<li>B.S. Nursing, Seoul National University, 2015-2019</li>
</ul>

### Employment History
<ul>
<li>Hospital Information System Coordinator, Seoul National University Hospital, Seoul, Korea from 2024.</li>
<li>Clinical Nurse, Seoul National University Hospital, Seoul, Korea from 2019 to 2024.</li>
</ul>

For more information, visit Son's [personal website](https://jisuson-wis.github.io/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
