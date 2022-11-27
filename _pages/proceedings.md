---
layout: archive
title: '<span style="color:white">Conference Proceedings</span>'
permalink: /proceedings/
author_profile: true
---

{% include base_path %}

{% for post in site.proceedings reversed %}
  {% include archive-single.html %}
{% endfor %}
