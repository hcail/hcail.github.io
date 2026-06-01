---
layout: page
title: Victor P. Cornet
title_s1: Postdoctoral Researcher
title_s2: Seoul National University
description: cornet.victor [at] gmail.com
img: assets/img/vcornet.png
importance: 40
category: current
---

### Short Bio
<p>Victor is a postdoctoral researcher at the <a href="https://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.</p>

### Education
<ul>
<li>M.S. Human-Computer Interaction, Indiana University – Purdue University Indianapolis</li>
<li>M.S. Computer Science, ESIEE Paris</li>
<li>B.S. Mathematics and Computer Science, Université Paris-Est Marne-La-Vallée</li>
</ul>

### Employment History
<ul>
<li>Postdoctoral Researcher, HCAIL, Seoul National University,
Seoul, Korea from June 2026 to present</li>
</ul>

For more information, visit Cornet's [personal website](https://victorcornet.com/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
