---
layout: default
title: UAP Mysteries
description: Constraint stacking analysis of unidentified aerial phenomena.
permalink: /mysteries/uap/
---

<h1>UAP Mysteries</h1>

<p>Unidentified aerial phenomena — cases where military personnel encountered something that doesn't fit known explanations. Each case is analyzed independently using constraint stacking. Plus: what the Fermi Paradox means given UAP evidence.</p>

<hr>

<h2>The Cases</h2>

<div class="app-grid">
  {% assign uap_mysteries = site.mysteries | where: "category", "uap" | sort: "title" %}
  {% for mystery in uap_mysteries %}
  <a href="{{ mystery.url | relative_url }}" class="app-card">
    <h3>{{ mystery.title }}</h3>
    <p>{{ mystery.description }}</p>
    <span class="result">{{ mystery.result }}</span>
  </a>
  {% endfor %}
</div>

<hr>

<h2>Meta-Constraint Analysis</h2>

<p>What happens when seven cases — six encounters across different decades, countries, and sensors, plus the transformed Fermi Paradox — all point the same direction?</p>

<div class="app-grid">
  <a href="{{ '/mysteries/uap/meta/' | relative_url }}" class="app-card">
    <h3>UAP Meta-Constraint</h3>
    <p>Convergence across independent cases. The odds that all have mundane explanations.</p>
    <span class="result">Convergence → non-human technology</span>
  </a>
</div>

<hr>

<p><a href="{{ '/mysteries/' | relative_url }}">← All mystery categories</a></p>
