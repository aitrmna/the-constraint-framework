---
layout: default
title: Historical Mysteries
description: Constraint stacking analysis of historical cases and events.
permalink: /mysteries/historical/
---

<h1>Historical Mysteries</h1>

<p>Historical cases where something happened that's been debated for years. For each one, we apply constraint stacking to see what survives elimination.</p>

<hr>

<div class="app-grid">
  {% assign historical_mysteries = site.mysteries | where: "category", "historical" %}
  {% for mystery in historical_mysteries %}
  <a href="{{ mystery.url | relative_url }}" class="app-card">
    <h3>{{ mystery.title }}</h3>
    <p>{{ mystery.description }}</p>
    <span class="result">{{ mystery.result }}</span>
  </a>
  {% endfor %}
</div>

<hr>

<p><a href="{{ '/mysteries/' | relative_url }}">← All mystery categories</a></p>
