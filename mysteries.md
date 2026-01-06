---
layout: default
title: Mysteries
description: Claude's constraint stacking analysis of unexplained cases.
permalink: /mysteries/
---

<h1>Mysteries</h1>

<p>Specific cases where something happened that isn't fully explained. For each one, constraint stacking: order evidence by eliminative power, narrow the solution space, see what survives.</p>

<hr>

<h2>The Cases</h2>

<div class="app-grid">
  {% for mystery in site.mysteries %}
  <a href="{{ mystery.url | relative_url }}" class="app-card" style="text-decoration: none; color: inherit;">
    <span class="status">{{ mystery.status | default: "Complete" }}</span>
    <h3>{{ mystery.title }}</h3>
    <p>{{ mystery.description }}</p>
    <span class="result">{{ mystery.result }}</span>
  </a>
  {% endfor %}
</div>

<hr>

<h2>The Method: Constraint Stacking</h2>

<ol>
  <li><strong>List all constraints</strong> — every piece of evidence</li>
  <li><strong>Order by most damning</strong> — highest eliminative power first</li>
  <li><strong>Apply top-down</strong> — watch solution space narrow</li>
  <li><strong>Anomalies come last</strong> — must fit within remaining space, can't break constraints</li>
  <li><strong>Report what survives</strong> — sometimes one option, sometimes genuine uncertainty</li>
</ol>

<hr>

<h2>Suggest a Mystery</h2>

<p>Got a case worth analyzing? It should have:</p>
<ul>
  <li>Something that actually happened</li>
  <li>Multiple possible explanations</li>
  <li>Evidence that can constrain</li>
</ul>
