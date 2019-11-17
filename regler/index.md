---
layout: page
title: Stadgar och andra regler
excerpt: "Stadgar och andra regler"
search_omit: true
---

Här kan du hitta de regler som gäller för BRF Morkullan 4. Är du ute efter ett specifikt dokument, kan du också gå <a href="https://github.com/karttur/morkullan4/tree/gh-pages/regler/doc/">direkt till arkivet som innehåller alla dokument (GitHub sida)</a>.

<ul class="post-list">
{% for post in site.categories.regler %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }}  <span class="excerpt"> {{ post.excerpt }}</span></a></article></li>
{% endfor %}
</ul>
