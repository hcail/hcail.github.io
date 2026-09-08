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
<p>Jamie is a visiting researcher at the <a href="https://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>,
and a PhD candidate at Uppsala University, Sweden in the Participatory eHealth and Health Data research group. Her PhD research examines self-care in Parkinson's disease through the lens of digital health and participatory research. Using qualitative, quantitative, and co-design methods, she explores how people living with Parkinson's can be better supported through person-centered approaches and innovative health technologies.
</p>

### Education
<ul>
<li>MSPH, Lund University, Sweden, from 2017 to 2019</li>
<li>B.A., University of North Carolina at Greensboro, USA, from 2012 to 2016</li>
<li>Emergency Medical Technician, GTCC, USA, from 2016 to 2017</li>
</ul>

### Employment History
<ul>
<li>Visiting Researcher, HCAIL, Seoul National University,
Seoul, Korea from September 2026 to present</li>
<li>Doctoral Candidate, PATH, Uppsala University, Sweden, from September 2023 to Present</li>
<li>Research Assistant, PATH, Uppsala University, Sweden, from April 2023 to September 2023</li>
<li>Research Assistant, MMC, Karolinska Institutet, Sweden, from April 2021 to April 2023</li>
</ul>

For more information, visit Luckhaus's [personal website](https://www.uu.se/en/contact-and-organisation/staff?query=N23-639).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
