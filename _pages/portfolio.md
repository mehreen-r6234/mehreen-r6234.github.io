---
# layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
redirect_from: 
  - /_portfolio
  # - /about.html
---

{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

