---
layout: page
title: people
permalink: /members/
description: as of November 2025
nav: true
display_categories: [current, alumni]
horizontal: false
---

<!-- pages/members.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.members | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.members | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>

---
<ul>
  <li><strong>Jiwon Chun</strong>: Undergraduate Research Intern; Sookmyung Women's University (Winter 2021 - Spring 2022)</li>
  <li><strong>Sehyeon Hong</strong>: Undergraduate Research Intern; Kyungpook National University (Summer 2021 - Winter 2022)</li>
  <li><strong>Gwanhee Lee</strong>: Undergraduate Research Intern; Amazon Web Services (Winter 2021 - Winter 2022)</li>
  <li><strong>Woohyun Cho</strong>: Undergraduate Research Intern; University of Michigan (Summer 2021)</li>
  <li><strong>Joonyoung Jun</strong>: Undergraduate Research Intern; University of Washington (Spring 2020 - Fall 2021)</li>
  <li><strong>Jeongjin Park</strong>: Undergraduate Research Intern; Purdue University (Spring 2021 - Spring 2021)</li>
  <li><strong>Hyuk Gi Lee</strong>: Research Intern; University of Washington (Summer 2020 - Spring 2021)</li>
  <li><strong>Jihyeon Park</strong>: Undergraduate Research Intern; Cornell University (Summer 2020 - Spring 2021)</li>
  <li><strong>Haeul Lee</strong>: Undergraduate Research Intern; University of Seoul (Fall 2020 - Winter 2020)</li>
  <li><strong>Changgeon Lim</strong>: Undergraduate Research Intern; University of Seoul (Fall 2020 - Winter 2020)</li>
  <li><strong>Wanhae Lee</strong>: Undergraduate Research Intern; Kakao Corp. (Fall 2019 - Winter 2020)</li>
  <li><strong>Suin Gwak</strong>: Undergraduate Research Intern; University of Seoul (Fall 2019 - Winter 2020)</li>
  <li><strong>Jaewon Choi</strong>: Undergraduate Research Intern; University of Washington (Summer 2020 - Fall 2020)</li>
  <li><strong>Minji Kwon</strong>: Undergraduate Research Intern; Kyung Hee University (Fall 2019 - Spring 2020)</li>
  <li><strong>Yewon Hyun</strong>: Undergraduate Research Intern; POSTECH (Fall 2019 - Winter 2019)</li>
  <li><strong>Heejae Jung</strong>: Undergraduate Research Intern; Kyung Hee University (Fall 2018 - Summer 2019)</li>
  <li><strong>Minyeong Seo</strong>: Undergraduate Research Intern; Kyung Hee University (Spring 2019 - Summer 2019)</li>
  <li><strong>Yiji Bae</strong>: Undergraduate Research Intern; Kyung Hee University (Fall 2018 - Spring 2019)</li>
  <li><strong>Hyeonjin Jeon</strong>: Undergraduate Research Intern; Kyung Hee University (Fall 2018 - Winter 2018)</li>
</ul>
<table border="0" style="width:100%">
<tr>
  <td class="c2">Jiwon Chun</td>
  <td class="c2">Undergraduate Research Intern</td>
  <td class="c2">Sookmyung Women's University</td>
  <td class="c2">Winter 2021 - Spring 2022</td>
</tr>
<tr>
  <td class="c2">Sehyeon Hong</td>
  <td class="c2">Undergraduate Research Intern</td>
  <td class="c2">Kyungpook National University</td>
  <td class="c2">Summer 2021 - Winter 2022</td>
</tr>
<tr>
  <td class="c2">Gwanhee Lee</td>
  <td class="c2">Undergraduate Research Intern</td>
  <td class="c2">Amazon Web Services</td>
  <td class="c2">Winter 2021 - Winter 2022</td>
</tr>
<tr>
  <td class="c2">Woohyun Cho</td>
  <td class="c2">Undergraduate Research Intern</td>
  <td class="c2">University of Michigan</td>
  <td class="c2">Summer 2021</td>
</tr>
  <tr>
    <td class="c2">Joonyoung Jun</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">University of Washington</td>
    <td class="c2">Spring 2020 - Fall 2021</td>
  </tr>
  <tr>
    <td class="c2">Jeongjin Park</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">Purdue University</td>
    <td class="c2">Spring 2021 - Spring 2021</td>
  </tr>
  <tr>
    <td class="c2">Hyuk Gi Lee</td>
    <td class="c2">Research Intern</td>
    <td class="c2">University of Washington</td>
    <td class="c2">Summer 2020 - Spring 2021</td>
  </tr>
  <tr>
    <td class="c2">Jihyeon Park</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">Cornell University</td>
    <td class="c2">Summer 2020 - Spring 2021</td>
  </tr>
  <tr>
    <td class="c2">Haeul Lee</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">University of Seoul</td>
    <td class="c2">Fall 2020 - Winter 2020</td>
  </tr>
  <tr>
    <td class="c2">Changgeon Lim</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">University of Seoul</td>
    <td class="c2">Fall 2020 - Winter 2020</td>
  </tr>
  <tr>
    <td class="c2">Wanhae Lee</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">Kakao Corp.</td>
    <td class="c2">Fall 2019 - Winter 2020</td>
  </tr>
  <tr>
    <td class="c2">Suin Gwak</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">University of Seoul</td>
    <td class="c2">Fall 2019 - Winter 2020</td>
  </tr>
  <tr>
    <td class="c2">Jaewon Choi</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">University of Washington</td>
    <td class="c2">Summer 2020 - Fall 2020</td>
  </tr>
  <tr>
    <td class="c2">Minji Kwon</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">Kyung Hee University</td>
    <td class="c2">Fall 2019 - Spring 2020</td>
  </tr>
  <tr>
    <td class="c2">Yewon Hyun</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">POSTECH</td>
    <td class="c2">Fall 2019 - Winter 2019</td>
  </tr>
  <tr>
    <td class="c2">Heejae Jung</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">Kyung Hee University</td>
    <td class="c2">Fall 2018 - Summer 2019</td>
  </tr>
  <tr>
    <td class="c2">Minyeong Seo</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">Kyung Hee University</td>
    <td class="c2">Spring 2019 - Summer 2019</td>
  </tr>
  <tr>
    <td class="c2">Yiji Bae</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">Kyung Hee University</td>
    <td class="c2">Fall 2018 - Spring 2019</td>
  </tr>
  <tr>
    <td class="c2">Hyeonjin Jeon</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">Kyung Hee University</td>
    <td class="c2">Fall 2018 - Winter 2018</td>
  </tr>
</table>
