---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=gctrxXsAAAAJ&hl=zh-CN}}">my Google Scholar profile</a>.</u>

Publications:  [2024](#2024),[2023](#2023),[2022](#2022), [2021](#2021)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=gctrxXsAAAAJ&hl=zh-CN}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
### 2024
{% for post in site.publications reversed %}
  {%if post.pub_year == '2024' %}
  {% include archive-single.html %}
  {% endif %}
{% endfor %}

### 2023
{% for post in site.publications reversed %}
  {%if post.pub_year == '2023' %}
  {% include archive-single.html %}
  {% endif %}
{% endfor %}

### 2022
{% for post in site.publications reversed %}
  {%if post.pub_year == '2022' %}
  {% include archive-single.html %}
  {% endif %}
{% endfor %}

### 2021
{% for post in site.publications reversed %}
  {%if post.pub_year == '2021' %}
  {% include archive-single.html %}
  {% endif %}
{% endfor %}
