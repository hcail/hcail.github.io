---
layout: page
title: Yubin Kim
title_s1: Undergraduate Research Intern
title_s2: University of Seoul
description: cosmos2718 [at] ewhain.net
img: assets/img/ybkim.png
importance: 25
category: current
---

### Short Bio
<p>Yubin Kim is an undergraduate research intern at the <a href="http://hcail.github.io">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
She expects to receive her B.S. in Physics from <a href="https://www.ewha.ac.kr/">Ewha Womans University.</a></p>

### Education
<ul>
<li> B.S. Physics, Ewha Womans University 2020-present.
</li>
</ul>

### Employment History
<ul>
<li>Undergraduate Research Intern, HCAIL, University of Seoul, Seoul, Korea from January 2024.
</li>
</ul>

For more information, visit Kim's [personal website](https://cosmos2718.github.io/Kimyubin/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
