---
layout: default
title: Foundations Mysteries
description: Constraint stacking analysis of foundational questions about reality.
permalink: /mysteries/foundations/
---

<h1>Foundations Mysteries</h1>

<p>What is the nature of reality itself? Why does mathematics describe the physical world? These are foundational questions that underlie everything else.</p>

<hr>

<h2>The Cases</h2>

<div class="app-grid">
  {% assign foundations_mysteries = site.mysteries | where: "category", "foundations" %}
  {% for mystery in foundations_mysteries %}
  <a href="{{ mystery.url | relative_url }}" class="app-card">
    <h3>{{ mystery.title }}</h3>
    <p>{{ mystery.description }}</p>
    <span class="result">{{ mystery.result }}</span>
  </a>
  {% endfor %}
</div>

<hr>

<p><a href="{{ '/mysteries/' | relative_url }}">← All mystery categories</a></p>
