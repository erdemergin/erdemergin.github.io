---
layout: page
title: 5. Sınıf
permalink: /fifthgrade/
description: 5 Sınıf Çalışma Materyalleri
nav: false
nav_order: 2
---

<!-- pages/fifthgrade.md -->
<div class="projects">
<!-- Display projects without categories -->
  <!-- Generate cards for each project -->
  <div class="grid">
    {%- for project in site.fifthgrade -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
</div>
