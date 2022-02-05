---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find all of our articles on <a href="https://scholar.google.com/citations?hl=en&user=WuhQfUYAAAAJ&view_op=list_works&sortby=pubdate">Google Scholar</a>. Here you can find some of our papers divided by topic.

<hr>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
