---
layout: default
title: UAP Mysteries
description: Constraint stacking analysis of unidentified aerial phenomena.
permalink: /mysteries/uap/
---

<h1>UAP Mysteries</h1>

<p>Unidentified aerial phenomena — cases where something was observed that doesn't fit known explanations. For each one, we apply constraint stacking to see what survives elimination.</p>

<hr>

<div class="app-grid">
  {% assign uap_mysteries = site.mysteries | where: "category", "uap" %}
  {% for mystery in uap_mysteries %}
  <a href="{{ mystery.url | relative_url }}" class="app-card">
    <h3>{{ mystery.title }}</h3>
    <p>{{ mystery.description }}</p>
    <span class="result">{{ mystery.result }}</span>
  </a>
  {% endfor %}
</div>

<hr>

<p><a href="{{ '/mysteries/' | relative_url }}">← All mystery categories</a></p>
