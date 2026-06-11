---
layout: page
title: Beomsu Kim
title_s1: Research Intern
title_s2: Seoul National University
description: ergonomics.idea [at] gmail.com
img: assets/img/bkim.png
importance: 39
category: alumni
---

### Short Bio
<p>Beomsu is a research intern at the <a href="https://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
He obtained his B.S. and M.S. in <a href="https://ie.kumoh.ac.kr/ie">Industrial Engineering </a>at the <a href="http://kumoh.ac.kr">Kumoh National Institute of Technology</a>.</p>

### Education
<ul>
<li>M.S. Industrial Engineering, Kumoh National Institute of Technology</li>
<li>B.S. Industrial Engineering, Kumoh National Institute of Technology</li>
</ul>

### Employment History
<ul>
<li>Research Intern, HCAIL, Seoul National University,
Seoul, Korea from May 2026 to present</li>
</ul>

For more information, visit Kim's [personal website](https://beomsu-k.github.io/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
