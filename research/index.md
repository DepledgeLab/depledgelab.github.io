---
title: Research
nav:
  order: 1
  tooltip: Projects, datasets, and more
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

{% capture content %}
**Warning**<br>
This site is currently under construction.
{% endcapture %}
{% include alert.html type="warning" content=content %}



{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
