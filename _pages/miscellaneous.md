---
layout: archive
title: ""
permalink: /miscellaneous/
author_profile: true
---

{% include base_path %}

# Travels 
I love travelling, both in companies of friends and families or be it solo. 
{% for post in site.travels reversed %}
  {% include archive-single-publication.html %}
{% endfor %}

# Hobbies
I am a life long learner and I always keep learning something new. In my free time, you can catch me down a running trail around Madison, doing yoga or cooking some traditional Indian food.

{% for post in site.hobbies reversed %}
  {% include archive-single-publication.html %}
{% endfor %}