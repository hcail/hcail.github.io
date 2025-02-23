---
layout: page
title: Jieun Seong
title_s1: Integrated Ph.D. Student
title_s2: Seoul National University
description: jieun3891 [at] snu.ac.kr
img: assets/img/jiseong.PNG
importance: 30
category: current
---

### Short Bio
<p>Jieun Seong is an integrated Ph.D. student at the <a href="https://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
</p>

### Education
<ul>
<li>Ph.D. Nursing Informatics, Seoul National University, 2025-present</li>
<li>B.S. Nursing, Yonsei University, 2017-2021</li>
</ul>

### Employment History
<ul>
<li>Neonatal Intensive Care Unit Nurse, Severance Hospital, Seoul, Korea from 2021 to 2023.</li>
</ul>

For more information, visit Seong's [personal website](https://jieunseong28.github.io/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
