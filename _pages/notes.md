---
title: "Notes"
layout: archive
permalink: /notes/
author_profile: true
---

{% assign notes = site.notes | sort: "path" %}

{% assign groups = notes | group_by_exp: "note", "note.path | split: '/' | first" %}

{% for group in groups %}
  <h2>{{ group.name }}</h2>
  <ul>
  {% for note in group.items %}
    <li>
      <a href="{{ note.url | relative_url }}">
        {{ note.title }}
      </a>
    </li>
  {% endfor %}
  </ul>
{% endfor %}
