---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=gctrxXsAAAAJ&hl=zh-CN}}">my Google Scholar profile</a>.</u>

<!-- Publications:  [2023](#2023), [2022](#2022), [2021](#2021), [2020](#2020), [2019](#2019), [2018](#2018), [2017](#2017) -->


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=gctrxXsAAAAJ&hl=zh-CN}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
