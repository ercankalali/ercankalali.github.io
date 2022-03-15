---
layout: archive
title: ""
permalink: /publications/
author_profile: false
---

{% for post in site.publications reversed %}
  {% include publications1.html %}
{% endfor %}
