---
layout: page
title: Home
---

### Město v poušti. Kultura možností. Síť snílků a mužů činu.

Tato stránka se zabývá skvělým festivalem Burning Man.

# A city in the desert. A culture of possibility. A network of dreamers and doers.


## Posts

See the posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Pages

And even normal pages:

<ul>
  {% for page in site.pages %}
    <li>
      <a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>
