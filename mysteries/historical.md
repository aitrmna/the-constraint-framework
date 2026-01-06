---
layout: default
title: Historical Mysteries
description: Constraint stacking analysis of historical cases and events.
permalink: /mysteries/historical/
---

<h1>Historical Mysteries</h1>

<p>Historical cases where something happened that's been debated for decades or centuries. For each one, we apply constraint stacking to see what survives elimination.</p>

<hr>

<h2>The Cases</h2>

<div class="app-grid">
  {% assign historical_mysteries = site.mysteries | where: "category", "historical" | sort: "title" %}
  {% for mystery in historical_mysteries %}
  <a href="{{ mystery.url | relative_url }}" class="app-card">
    <h3>{{ mystery.title }}</h3>
    <p>{{ mystery.description }}</p>
    <span class="result">{{ mystery.result }}</span>
  </a>
  {% endfor %}
</div>

<hr>

<h2>Meta-Constraint Analysis</h2>

<p>What patterns emerge across historical mysteries? Most resolve to mundane explanations. What does that tell us?</p>

<div class="app-grid">
  <a href="{{ '/mysteries/historical/meta/' | relative_url }}" class="app-card">
    <h3>Historical Meta-Constraint</h3>
    <p>Patterns across seven historical mysteries. Why most resolve to mundane, and what that means.</p>
    <span class="result">5/7 mundane, 1 unknown, 1 uncertain</span>
  </a>
</div>

<hr>

<p><a href="{{ '/mysteries/' | relative_url }}">← All mystery categories</a></p>
