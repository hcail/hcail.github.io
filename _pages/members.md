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
  <li><strong>Chaeyoung Lee</strong>: Undergraduate Research Intern; Seoul National University (Summer 2025 - Winter 2025)</li>
  <li><strong>Hyeonmin Choi</strong>: Undergraduate Research Intern; Seoul National University (Summer 2025)</li>
  <li><strong>Ohchul Kwon</strong>: Undergraduate Research Intern; Seoul National University (Summer 2025)</li>
  <li><strong>Duhyung Kwak</strong>: Undergraduate Research Intern; Seoul National University (Winter 2024 - Summer 2025)</li>
  <li><strong>Myeonghun Jeong</strong>: Undergraduate Research Intern; Seoul National University (Winter 2024 - Winter 2024)</li>
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
