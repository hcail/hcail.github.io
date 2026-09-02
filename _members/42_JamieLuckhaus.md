---
layout: page
title: Jamie Luckhaus
title_s1: Visiting Researcher
title_s2: Uppsala University
description: jamie.luckhaus [at] uu.se
img: assets/img/jluckhaus.png
importance: 42
category: current
---

### Short Bio
<p>Jamie is a visiting researcher at the <a href="https://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.</p>

### Education
<ul>
<li>B.S.</li>
</ul>

### Employment History
<ul>
<li>Visiting Researcher, HCAIL, Seoul National University,
Seoul, Korea from September 2026 to present</li>
</ul>

For more information, visit Luckhaus's [personal website](https://www.uu.se/en/contact-and-organisation/staff?query=N23-639).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
