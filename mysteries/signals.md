---
layout: default
title: Signal Mysteries
description: Constraint stacking analysis of unexplained signals and transmissions.
permalink: /mysteries/signals/
---

<h1>Signal Mysteries</h1>

<p>Unexplained signals — radio bursts, transmissions, detections that don't fit known patterns. What survives constraint stacking?</p>

<hr>

<h2>The Cases</h2>

<div class="app-grid">
  {% assign signal_mysteries = site.mysteries | where: "category", "signals" | sort: "title" %}
  {% for mystery in signal_mysteries %}
  <a href="{{ mystery.url | relative_url }}" class="app-card">
    <h3>{{ mystery.title }}</h3>
    <p>{{ mystery.description }}</p>
    <span class="result">{{ mystery.result }}</span>
  </a>
  {% endfor %}
</div>

<hr>

<h2>Meta-Constraint Analysis</h2>

<p>What patterns emerge across signal mysteries? How do they compare to UAP cases?</p>

<div class="app-grid">
  <a href="{{ '/mysteries/signals/meta/' | relative_url }}" class="app-card">
    <h3>Signals Meta-Constraint</h3>
    <p>Patterns across three signal mysteries. Most resolve when data is available.</p>
    <span class="result">1 resolved, 1 natural, 1 uncertain</span>
  </a>
</div>

<hr>

<p><a href="{{ '/mysteries/' | relative_url }}">← All mystery categories</a></p>
