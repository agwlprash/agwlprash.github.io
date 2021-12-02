---
title:  "People1"
layout: collection
permalink: /People/
collection: staff_members
author_profile: true
#entries_layout: grid
#classes: wide
#comments: true
---


{% for staff_member in site.staff_members %}
  <h2>{{ staff_member.name }} - {{ staff_member.position }}</h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}
