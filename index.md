---
title: Home
layout: default
---
{% for project in site.projects %}
{% include list-project.html item=project %}
{% else %}
no projects
{% endfor %}
