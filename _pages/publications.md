---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  Find my articles on <u><a href="https://scholar.google.com/citations?hl=en&user=EnZZdAgAAAAJ">Google Scholar</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
