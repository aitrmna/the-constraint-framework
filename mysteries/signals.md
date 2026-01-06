---
layout: default
title: Signal Mysteries
description: Constraint stacking analysis of unexplained signals and transmissions.
permalink: /mysteries/signals/
---

<h1>Signal Mysteries</h1>

<p>Unexplained signals — cases where something was detected that doesn't fit known explanations. Radio, electromagnetic, or other transmissions of unknown origin.</p>

<hr>

<div class="app-grid">
  {% assign signal_mysteries = site.mysteries | where: "category", "signals" %}
  {% for mystery in signal_mysteries %}
  <a href="{{ mystery.url | relative_url }}" class="app-card">
    <h3>{{ mystery.title }}</h3>
    <p>{{ mystery.description }}</p>
    <span class="result">{{ mystery.result }}</span>
  </a>
  {% endfor %}
</div>

<hr>

<p><a href="{{ '/mysteries/' | relative_url }}">← All mystery categories</a></p>
