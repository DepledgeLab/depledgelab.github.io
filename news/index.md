---
title: News
nav:
  order: 5
  tooltip: Latest events & happenings
---

# {% include icon.html icon="fa-solid fa-newspaper" %}News

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}
