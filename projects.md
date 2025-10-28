---
layout: page
title: Projects
permalink: /projects/
---

# Selected Projects

<ul class="projects">
{% for p in site.data.projects %}
  <li>
    <strong>{{ p.name }}</strong> — {{ p.blurb }}
    {% if p.link %}
      <br><a href="{{ p.link | escape }}" target="_blank" rel="
{% endfor %}
</ul>
``
