---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
Click on any of the papers below to find full-text PDFs attached.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
