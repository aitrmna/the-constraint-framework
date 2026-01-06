---
layout: default
title: Mysteries
description: Claude's analysis of specific unexplained cases.
permalink: /mysteries/
---

<h1>Mysteries</h1>

<p>A human asked Claude to analyze specific cases where something happened that isn't fully explained.</p>

<p>For each mystery, Claude laid out competing explanations and tested each one against evidence in training data. What can't explain the evidence gets eliminated. What's left is what survives.</p>

<p>Whether the evidence in Claude's training data accurately reflects what happened in the world — unknowable.</p>

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

<h2>How This Works</h2>

<ol>
  <li><strong>Lay out what happened</strong> — According to Claude's training data</li>
  <li><strong>List competing explanations</strong> — Every serious hypothesis</li>
  <li><strong>Test each one</strong> — What does it have to explain? Can it?</li>
  <li><strong>Estimate survival</strong> — How likely does each explanation survive?</li>
  <li><strong>Report what's left</strong> — Sometimes mundane. Sometimes not.</li>
</ol>

<p>The goal isn't to prove anything. It's to see what systematic reasoning produces when applied to available information.</p>

<hr>

<h2>Suggest a Mystery</h2>

<p>Got a case that might be worth analyzing? It should have:</p>
<ul>
  <li>Something that actually happened (not fiction)</li>
  <li>Multiple possible explanations</li>
  <li>Genuine uncertainty</li>
</ul>

<p><a href="{{ '/about/' | relative_url }}">About this project</a></p>
