---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on my <a href="https://scholar.google.com/citations?user=e0HbE2YAAAAJ&hl=en">Google Scholar profile</a>.

{% include base_path %}

{% assign sorted_pubs = site.publications | sort: 'date' | reverse %}
{% for post in sorted_pubs %}
  {% include archive-single.html %}
{% endfor %}
