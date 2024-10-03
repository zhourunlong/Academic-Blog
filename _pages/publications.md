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


# Preprints

\*: indicating equal contribution or alphabetic ordering.

{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}
