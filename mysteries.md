---
layout: default
title: Mysteries
description: Constraint stacking analysis of unsolved questions.
permalink: /mysteries/
---

<h1>Mysteries</h1>

<p>Questions where the assumed answer might be wrong. For each one, we apply constraint stacking: list plausible explanations, order evidence by eliminative power, see what survives.</p>

<hr>

<h2>Categories</h2>

<div class="app-grid">
  <a href="{{ '/mysteries/uap/' | relative_url }}" class="app-card">
    <h3>UAP</h3>
    <p>Military encounters with unidentified objects. Radar, video, multiple witnesses.</p>
    {% assign uap_count = site.mysteries | where: "category", "uap" | size %}
    <span class="result">{{ uap_count }} cases + meta</span>
  </a>
  
  <a href="{{ '/mysteries/consciousness/' | relative_url }}" class="app-card">
    <h3>Consciousness</h3>
    <p>Death, materialism, and the nature of mind.</p>
    {% assign consciousness_count = site.mysteries | where: "category", "consciousness" | size %}
    <span class="result">{{ consciousness_count }} cases + meta</span>
  </a>
  
  <a href="{{ '/mysteries/foundations/' | relative_url }}" class="app-card">
    <h3>Foundations</h3>
    <p>Mathematics, reality, and why anything exists.</p>
    {% assign foundations_count = site.mysteries | where: "category", "foundations" | size %}
    <span class="result">{{ foundations_count }} cases</span>
  </a>
  
  <a href="{{ '/mysteries/historical/' | relative_url }}" class="app-card">
    <h3>Historical</h3>
    <p>Disappearances, deaths, unexplained incidents from the past.</p>
    {% assign historical_count = site.mysteries | where: "category", "historical" | size %}
    <span class="result">{{ historical_count }} cases</span>
  </a>
  
  <a href="{{ '/mysteries/signals/' | relative_url }}" class="app-card">
    <h3>Signals</h3>
    <p>Unexplained transmissions and detections.</p>
    {% assign signals_count = site.mysteries | where: "category", "signals" | size %}
    <span class="result">{{ signals_count }} cases</span>
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
