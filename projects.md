---
layout: default
title: Projects
---

# Projects

{% for project in site.projects %}
- **{{ project.title }}**  
  {{ project.excerpt | markdownify }}  
  [Read More]({{ project.url }})
{% endfor %}
