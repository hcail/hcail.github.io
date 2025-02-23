---
layout: page
title: Minju Kim
title_s1: Integrated Ph.D. Student
title_s2: Seoul National University
description: lialos [at] snu.ac.kr
img: assets/img/mkim.PNG
importance: 31
category: current
---

### Short Bio
<p>Minju Kim is an integrated Ph.D. student at the <a href="https://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
</p>

### Education
<ul>
<li>Ph.D. Nursing Informatics, Seoul National University, 2025-present</li>
<li>B.S. Nursing, Gachon University, 2014-2018</li>
</ul>

### Employment History
<ul>
<li>Staff Registered Nurse, Seoul National University Bundang Hospital, Seongnam, Korea from 2018 to 2021.</li>
</ul>

<!-- For more information, visit Kim's [personal website](https://hcail.snu.ac.kr). -->

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
