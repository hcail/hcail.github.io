---
layout: page
title: Yunseo Do
title_s1: Undergraduate Research Intern
title_s2: Kyung Hee University
description: ysdoh0209 [at] khu.ac.kr
img: assets/img/ydo.png
importance: 34
category: current
---

### Short Bio
<p>Yunseo Do is an undergraduate research intern at the <a href="http://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
</p>

### Education
<ul>
<li>B.S. Artificial Intelligence, Kyung Hee University 2022-Present.
</li>
</ul>

### Employment History
<ul>
<li>Undergraduate Research Intern, HCAIL, Seoul, Korea from Mar. 2025.
</li>
<li>Research Intern, KIST Europe, Saarbrücken, Germany from Aug. 2024 to Jan. 2025.
</ul>

For more information, visit Do's [personal website](hhttps://simple-board-99d.notion.site/Hello-I-m-Yunseo-Do-bca71b3fd8c042938ffd6da7bb61f3e8?pvs=4).
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
