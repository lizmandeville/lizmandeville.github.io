---
title: Projects
nav:
  order: 2
  tooltip: Current and past research projects
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

{% include tags.html tags="chrosomus, catostomus, hybridization, sex-determination" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
