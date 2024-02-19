---
layout: default
---

# Final-year undergraduate 

I'm Ram, a third year computer science student based in the UK. I'm currently studying for my bachelor's degree at Bristol University, expecting to graduate in 2024.

pharadonlarg at gmail.com

## Projects

{% for project in site.data.projects %}
{% if project.category == "project" %}
{% include project.html project=project %}
{% endif %}
{% endfor %}


See [my GitHub profile](http://github.com/rlarg) for other projects I've worked on.