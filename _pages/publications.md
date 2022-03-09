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


<h2>2022</h2>
{% for post in site.publications reversed %}
  {% if post.year == '2022' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

-----------------------------------------

<h2>2021</h2>
{% for post in site.publications reversed %}
  {% if post.year == '2021' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

-----------------------------------------

<h2>2020</h2>
{% for post in site.publications reversed %}
  {% if post.year == '2020' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

-----------------------------------------

<h2>2019</h2>
{% for post in site.publications reversed %}
  {% if post.year == '2019' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

-----------------------------------------

<h2>2018</h2>
{% for post in site.publications reversed %}
  {% if post.year == '2018' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

-----------------------------------------

<h2>2016</h2>
{% for post in site.publications reversed %}
  {% if post.year == '2016' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

-----------------------------------------

<h2>2015</h2>
{% for post in site.publications reversed %}
  {% if post.year == '2015' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

-----------------------------------------

<h2>2014</h2>
{% for post in site.publications reversed %}
  {% if post.year == '2014' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

-----------------------------------------

<h2>2013</h2>
{% for post in site.publications reversed %}
  {% if post.year == '2013' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}



 