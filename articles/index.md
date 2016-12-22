---
layout: page
title: Research areas
#excerpt: "An archive of articles sorted by date."
search_omit: false
---

<ul class="post-list">
{% for post in site.categories.research %} 
  <li><research><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <!--<span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>-->{% if post.excerpt %} <span class="excerpt">{{ post.excerpt | remove: '<p>' | remove: '</p>' }}</span>{% endif %}</a></research></li>
{% endfor %}
</ul>
