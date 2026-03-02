---
layout: page
title: Seungjun Chong
title_s1: Integrated Ph.D. Student
title_s2: Seoul National University
description: jchong990315 [at] snu.ac.kr
img: assets/img/schong.png
importance: 38
category: current
---

### Short Bio
<p>Seungjun Chong is an integrated Ph.D. student of informatics in the
<a href="https://nursing.snu.ac.kr/en">College of Nursing</a>
at <a href="https://en.snu.ac.kr/">Seoul National University</a>.
He was a research intern at the <a href="https://hcail.snu.ac.kr">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.
He obtained his B.S. in <a href="https://www.cs.wisc.edu/">Computer Science </a>at the <a href="https://www.wisc.edu/">University of Wisconsin - Madison</a> in August 2026.</p>

### Education
<ul>
<li>Ph.D. Nursing Informatics, Seoul National University, 2026-present</li>
<li>B.S. Computer Science, University of Wisconsin–Madison, 2019-2025</li>
</ul>

### Employment History
<ul>
<li>Research Intern, HCAIL, Seoul National University,
Seoul, Korea from June 2025 to February 2026.</li>
<li>Undergraduate Research Intern, WiNGS Lab, University of Wisconsin–Madison, WI, USA from 2024 to 2025.</li>
<li>Software Engineer, THEARHAN, Seoul, Korea from 2019 to 2021.</li>
</ul>

For more information, visit Chong's [personal website](https://chong-portfolio.vercel.app/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
