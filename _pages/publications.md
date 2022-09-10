---
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- layout: archive -->

-----
{% include base_path %}

Full list in my CV.

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?hl=en&user=33UVNpUAAAAJ"){:target="_blank"}.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
