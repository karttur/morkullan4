---
layout: page
title: Ritningar
excerpt: "Ritningar"
search_omit: true
---


Här kan du hitta olika ritningar över fastigheten Morkullan 4 som ägs av BRF Morkullan 4. Är du ute efter en fullskaling ritning kan du också gå <a href="doc/full/">direkt till arkivet som innehåller alla ritningar</a>.

<ul class="post-list">
{% for post in site.categories.ritningar %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '\[ ... \]' | remove: '\( ... \)' | markdownify | strip_html | strip_newlines | escape_once }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>
