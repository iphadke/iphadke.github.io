---
layout: archive
title: ""
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
 {% include base_path %}
 
{% for post in site.teachingta reversed %}
  <h2>{{ post.title }}</h2>
    <h3>{{ post.role }}</h3>
{% endfor %}


 <!---
  

 
  --->