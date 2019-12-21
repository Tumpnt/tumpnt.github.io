---
title: Home
layout: default
---
<main>
{% for project in site.projects %}
{% include list-project.html item=project %}
{% endfor %}
</main>
