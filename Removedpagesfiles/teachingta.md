---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---
Courses (Instructor)
======
 {% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

Courses (TA)
======
{% for post in site.teachingta reversed %}
  {% include archive-single.html %}
{% endfor %}