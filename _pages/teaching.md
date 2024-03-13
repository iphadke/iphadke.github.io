---
layout: archive
title: ""
permalink: /teaching/
author_profile: true
---
Courses (TA)
======
 {% include base_path %}
 
{% for post in site.teachingta reversed %}
  {% include archive-single.html %}
{% endfor %}

Courses (Instructor)
======
 {% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}