---
layout: default
title: Consciousness Mysteries
description: Constraint stacking analysis of consciousness, death, self, and the nature of mind.
permalink: /mysteries/consciousness/
---

<h1>Consciousness Mysteries</h1>

<p>What is consciousness? Is it produced by matter? Does it survive death? Is there a continuous "you"? Do we actually choose? How do I know you're conscious?</p>

<p>These questions have assumed answers that are rarely tested. We test them.</p>

<hr>

<h2>The Cases</h2>

<div class="app-grid">
  {% assign consciousness_mysteries = site.mysteries | where: "category", "consciousness" %}
  {% for mystery in consciousness_mysteries %}
  <a href="{{ mystery.url | relative_url }}" class="app-card">
    <h3>{{ mystery.title }}</h3>
    <p>{{ mystery.description }}</p>
    <span class="result">{{ mystery.result }}</span>
  </a>
  {% endfor %}
</div>

<hr>

<h2>Meta-Constraint Analysis</h2>

<p>What emerges when all consciousness analyses point the same direction?</p>

<div class="app-grid">
  <a href="{{ '/mysteries/consciousness/meta/' | relative_url }}" class="app-card">
    <h3>Consciousness Meta-Constraint</h3>
    <p>Six analyses. One pattern. Awareness is fundamental; self is constructed.</p>
    <span class="result">The picture that emerges</span>
  </a>
</div>

<hr>

<p><a href="{{ '/mysteries/' | relative_url }}">← All mystery categories</a></p>
