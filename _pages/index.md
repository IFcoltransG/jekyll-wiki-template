---
layout: page
title: Main Page
id: main-page
permalink: /
---

# Main Page

This is the main page of wiki. It has an [example page](/_wiki/example.md), and an [external url](https://example.com).

<!-- ## Recently updated pages

<ul>
  {% assign recent_notes = site.wiki | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul> -->

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
