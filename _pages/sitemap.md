---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
description: An index of Yiming Xu’s academic pages, publications, talks, and teaching.
---

A list of the pages on this site. An [XML version]({{ '/sitemap.xml' | relative_url }}) is also available.

<h2>Pages</h2>
<div class="list__item">
  <h2 class="archive__item-title"><a href="{{ '/' | relative_url }}">About Me</a></h2>
</div>
{% for link in site.data.navigation.main %}
<div class="list__item">
  <h2 class="archive__item-title"><a href="{{ link.url | relative_url }}">{{ link.title }}</a></h2>
</div>
{% endfor %}

{% for collection in site.collections %}
{% if collection.output and collection.docs.size > 0 %}
<h2>{{ collection.label | capitalize }}</h2>
{% for post in collection.docs %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}
{% endfor %}
