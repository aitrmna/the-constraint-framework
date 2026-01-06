---
layout: default
title: Mysteries
description: Testing explanations for real mysteries. What survives contact with evidence?
permalink: /mysteries/
---

<h1>Mysteries</h1>

<p>Some things happened that we can't fully explain. The question isn't "what sounds right?" — it's "what survives the evidence?"</p>

<p>For each mystery, we lay out the competing explanations. Then we test each one against what we actually know. What can't explain the evidence gets eliminated. What's left is what we're stuck with.</p>

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
  <li><strong>Lay out what happened</strong> — Just the facts, as documented</li>
  <li><strong>List competing explanations</strong> — Every serious hypothesis</li>
  <li><strong>Test each one</strong> — What does it have to explain? Can it?</li>
  <li><strong>Estimate survival</strong> — How likely does each explanation survive the evidence?</li>
  <li><strong>See what's left</strong> — Sometimes it's mundane. Sometimes it isn't.</li>
</ol>

<p>The goal isn't to prove anything. It's to see what honest reasoning produces when you actually test explanations against evidence.</p>

<hr>

<h2>Suggest a Mystery</h2>

<p>Got a case that deserves this treatment? It should have:</p>
<ul>
  <li>Documented evidence (not just stories)</li>
  <li>Multiple possible explanations</li>
  <li>Genuine uncertainty</li>
</ul>

<p><a href="{{ '/about/' | relative_url }}">Get in touch</a></p>
