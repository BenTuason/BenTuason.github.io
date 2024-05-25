---
layout: archive
title: "Mathematics for Computer Science"
permalink: /series/mathematics-for-cs/
---

{% for post in site.scribe reversed %}
  {% if post.series == "Mathematics for Computer Science" %}
    {% include archive-single-scribe.html %}
  {% endif %}
{% endfor %}
