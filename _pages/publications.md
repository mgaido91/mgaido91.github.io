---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include publications limit=20 link=true %}

You can also find the full list of my articles on <u><a href="https://scholar.google.com/citations?user=Ojc1LRYAAAAJ">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
