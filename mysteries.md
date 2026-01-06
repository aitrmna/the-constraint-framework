---
layout: default
title: Mysteries
description: Constraint stacking analysis of unexplained cases.
permalink: /mysteries/
---

<h1>Mysteries</h1>

<p>Specific cases where something happened that isn't fully explained. For each category, we apply constraint stacking — order evidence by eliminative power, narrow the solution space, see what survives.</p>

<hr>

<h2>Categories</h2>

<div class="app-grid">
  <a href="{{ '/mysteries/uap/' | relative_url }}" class="app-card">
    <h3>UAP</h3>
    <p>Unidentified aerial phenomena. Military encounters, radar contacts, unexplained sightings.</p>
    {% assign uap_count = site.mysteries | where: "category", "uap" | size %}
    <span class="result">{{ uap_count }} cases</span>
  </a>
  
  <a href="{{ '/mysteries/historical/' | relative_url }}" class="app-card">
    <h3>Historical</h3>
    <p>Historical cases and events. Disappearances, deaths, unexplained incidents.</p>
    {% assign historical_count = site.mysteries | where: "category", "historical" | size %}
    <span class="result">{{ historical_count }} cases</span>
  </a>
</div>

<hr>

<h2>The Method</h2>

<ol>
  <li><strong>List all plausible explanations</strong></li>
  <li><strong>Order evidence by eliminative power</strong> — most damning first</li>
  <li><strong>Apply constraints top-down</strong> — watch explanations get eliminated</li>
  <li><strong>Anomalies come last</strong> — must fit within remaining space</li>
  <li><strong>Report what survives</strong></li>
</ol>

<p>We're not asserting truth. We're reporting what survives elimination.</p>

<p><a href="{{ '/methodology/' | relative_url }}">Full methodology →</a></p>
