---
layout: page
title: YoungJu Lee
title_s1: Research Intern
title_s2: Seoul National University
description: liagridd [at] gmail.com
img: assets/img/ylee.png
importance: 41
category: current
---

### Short Bio
<p>YoungJu is a research intern at the <a href="https://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.</p>

### Education
<ul>
<li>B.S.</li>
</ul>

### Employment History
<ul>
<li>Research Intern, HCAIL, Seoul National University,
Seoul, Korea from June 2026 to present</li>
</ul>

For more information, visit Lee's [personal website](https://bit.ly/youngjulee).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
