---
layout: archive
title: '<span style="color:white">Publications & Reports</span>'
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


&nbsp;
&nbsp;
**'<font size="+3"><span style="color:white">Conference Proceedings</span></font>'**

{% for post in site.proceedings reversed %}
  {% include archive-single.html %}
{% endfor %}