---
layout: page
title: Yunseo Moon
title_s1: Integrated Ph.D. Student
title_s2: Seoul National University
description: copel0317 [at] gmail.com
img: assets/img/ysmoon.png
importance: 22
category: current
---

### Short Bio
<p>Yunseo Moon is an integrated Ph.D. student of informatics in the
<a href="https://nursing.snu.ac.kr/en">College of Nursing</a>
at <a href="https://en.snu.ac.kr/">Seoul National University</a>.
Yunseo Moon was an undergraduate research intern at the <a href="http://hcail.github.io">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
He received his B.S. in <a href="https://engineering.uos.ac.kr/engineering/depart/cs/welcome.do">Computer Science</a> from the <a href="https://www.uos.ac.kr/">University of Seoul</a> in February 2026.</p>

### Education
<ul>
<li>Ph.D. Nursing Informatics, Seoul National University, 2026-present</li>
<li>B.S. Computer Science, University of Seoul, 2020-2026</li>
</ul>

### Employment History
<ul>
<li>Research Assistant, Seoul National University, Seoul, Korea from March 2026-present.</li>
<li>Teaching Assistant, Seoul National University, Seoul, Korea from March 2026-present.</li>
<li>Undergraduate Research Intern, HCAIL, University of Seoul, Seoul,
Korea from January 2023 to February 2026.
</li>
</ul>

For more information, visit Moon's [personal website](https://www.figma.com/proto/3bZ7f05favm66CCXNfej4u/Yunseo-Moon?node-id=0-1&t=SrepSZniZHH9Nn1W-1).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
