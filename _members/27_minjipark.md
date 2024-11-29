---
layout: page
title: Minji Park
title_s1: Undergraduate Research Intern
title_s2: Sungkyunkwan University
description: mj.park [at] g.skku.edu
img: assets/img/mpark.jpg
importance: 27
category: current
---

### Short Bio
<p>Minji Park is an undergraduate research intern at the <a href="http://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
</p>

### Education
<ul>
<li>B.S. Computer Science, Sungkyunkwan University Present.
</li>
</ul>

### Employment History
<ul>
<li>Undergraduate Research Intern, HCAIL, Seoul National University, Seoul, Korea from November 2024.
</li>
</ul>

For more information, visit Park's [personal website](https://minji-dev.github.io/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
