---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

\*: indicating equal contribution or alphabetic ordering.


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
