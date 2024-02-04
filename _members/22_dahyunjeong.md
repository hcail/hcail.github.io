---
layout: page
title: Dahyun Jeong
title_s1: Undergraduate Research Intern
title_s2: University of Seoul
description: jeongdahyunj [at] gmail.com
img: assets/img/dhjeong.png
importance: 23
category: current
---

### Short Bio
<p>Dahyun Jeong is an undergraduate research intern at the <a href="http://hcail.github.io">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
She expects to receive her B.S. in <a href="https://engineering.uos.ac.kr/engineering/depart/cs/welcome.do">Computer Science</a> from the <a href="https://www.uos.ac.kr/">University of Seoul</a></p>

### Education
<ul>
<li> B.S. Computer Science, University of Seoul 2021-present.
</li>
</ul>

### Employment History
<ul>
<li>Undergraduate Research Intern, HCAIL, University of Seoul, Seoul, Korea from December 2023.
</li>
</ul>

For more information, visit Jeong's [personal website](https://bronging.github.io).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
