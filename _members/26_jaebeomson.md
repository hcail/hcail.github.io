---
layout: page
title: Jaebeom Son
title_s1: Undergraduate Research Intern
title_s2: Sogang University
description: thswoqja98 [at] sogang.ac.kr
img: assets/img/json.jpg
importance: 26
category: current
---

### Short Bio
<p>Jaebeom Son is an undergraduate research intern at the <a href="http://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
</p>

### Education
<ul>
<li>B.A Economics and B.S. Computer Science, Sogang University Present.
</li>
</ul>

### Employment History
<ul>
<li>Undergraduate Research Intern, HCAIL, Seoul National University, Seoul, Korea from November 2024.
</li>
</ul>

For more information, visit Son's [personal website](https://jaebeom.notion.site/JAEBEOM-SON-ffd1cbc5af3b4ceca83d56f4c44a116e).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
