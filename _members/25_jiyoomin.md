---
layout: page
title: Jiyoo Min
title_s1: Undergraduate Research Intern
title_s2: University of Seoul
description: jessy0618 [at] uos.ac.kr
img: assets/img/jmin.png
importance: 25
category: current
---

### Short Bio
<p>Jiyoo Min is an undergraduate research intern at the <a href="http://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
</p>

### Education
<ul>
<li>B.S. Computer Science, University of Seoul 2023-Present.
</li>
</ul>

### Employment History
<ul>
<li>Undergraduate Research Intern, HCAIL, Seoul, Korea from June 2024.
</li>
</ul>

For more information, visit Min's [personal website](https://jessythymejiyoo.github.io/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
