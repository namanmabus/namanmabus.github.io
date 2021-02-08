---
layout: archive
title: "Publications"
permalink: publications/
author_profile: true
---

You can also find my articles on my [Google Scholar profile](https://scholar.google.com/citations?user=FfPlF8gAAAAJ).

{% include base_path %}


{% for post in site.publications reversed %}
  {% include archive-single-paper.html %}
{% endfor %}
