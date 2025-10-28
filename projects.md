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
    {% if p.link %}<br><a href="{{ p.link }}" target="_blank" rel="ndfor %}
</ul>
