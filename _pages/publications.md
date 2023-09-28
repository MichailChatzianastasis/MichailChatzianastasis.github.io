---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---



You can also find my articles on <u><a href="https://scholar.google.com/citations?user=e0HbE2YAAAAJ&hl=en">my Google Scholar profile</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  <li>
  {% include archive-single.html %}
  </li>
{% endfor %}
