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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<h2>2020</h2>
{% for post in site.publications reversed %}
  {% if post.year == '2020' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}