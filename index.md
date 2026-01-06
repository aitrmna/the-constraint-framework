---
layout: default
title: null
description: Testing beliefs against evidence using systematic Bayesian reasoning across multiple independent evidence domains.
permalink: /
---

<h1>What survives contact with evidence?</h1>

<p>The Constraint Framework is a methodology for testing beliefs against reality. It applies systematic Bayesian reasoning across multiple independent evidence domains to see which hypotheses survive—and which don't.</p>

<p>Most contested questions get stuck in intuition vs. intuition. This framework asks: <strong>What would have to be true if this hypothesis were correct? Can we test that?</strong></p>

<hr>

<h2>How It Works</h2>

<ol>
  <li><strong>Define the hypothesis</strong> — What claim are we testing?</li>
  <li><strong>Identify predictions</strong> — What must be true if the hypothesis is correct?</li>
  <li><strong>Find evidence domains</strong> — Where can we test these predictions?</li>
  <li><strong>Estimate escape probabilities</strong> — How likely does the hypothesis survive each domain?</li>
  <li><strong>Group by confounders</strong> — Which domains might share common errors?</li>
  <li><strong>Combine appropriately</strong> — Multiply across groups, not within</li>
  <li><strong>Update beliefs</strong> — Apply Bayes' theorem</li>
</ol>

<p><a href="{{ '/methodology/' | relative_url }}">Full methodology →</a></p>

<hr>

<h2>Big Questions</h2>

<div class="app-grid">
  <a href="{{ '/applications/death/' | relative_url }}" class="app-card" style="text-decoration: none; color: inherit;">
    <span class="status">Complete</span>
    <h3>Does consciousness survive death?</h3>
    <p>Testing whether permanent annihilation at death is likely.</p>
    <span class="result">P(annihilation) < 1%</span>
  </a>
  
  <div class="app-card coming-soon">
    <span class="status">Coming Soon</span>
    <h3>Is materialism true?</h3>
    <p>Testing whether consciousness is produced by matter.</p>
    <span class="result">P(materialism) ≈ 1.3%</span>
  </div>
  
  <div class="app-card coming-soon">
    <span class="status">Coming Soon</span>
    <h3>Is free will real?</h3>
    <p>Testing whether agency is genuine or illusory.</p>
    <span class="result">P(illusionism) ≈ 2.5%</span>
  </div>
</div>

<hr>

<h2>Mysteries</h2>

<div class="app-grid">
  {% for mystery in site.mysteries limit:3 %}
  <a href="{{ mystery.url | relative_url }}" class="app-card" style="text-decoration: none; color: inherit;">
    <span class="status">{{ mystery.status | default: "Complete" }}</span>
    <h3>{{ mystery.title }}</h3>
    <p>{{ mystery.description }}</p>
    <span class="result">{{ mystery.result }}</span>
  </a>
  {% endfor %}
</div>

<p><a href="{{ '/mysteries/' | relative_url }}">All mysteries →</a></p>

<hr>

<h2>The Emerging Picture</h2>

<p>When you run the framework across fundamental questions, a coherent picture emerges:</p>

<ul>
  <li>Consciousness is fundamental (not produced by matter)</li>
  <li>Space and separation are appearances (not ultimate reality)</li>
  <li>The self is a pattern (not a fundamental unit)</li>
  <li>Free will is real (not illusion)</li>
  <li>Death is transformation (not annihilation)</li>
</ul>

<p>These results cohere. They point in a consistent direction. And they match what contemplative traditions have claimed for millennia—now with explicit probability estimates.</p>

<hr>

<h2>Start Here</h2>

<p>If you're new, read <a href="{{ '/applications/death/' | relative_url }}"><strong>The Probability of Death</strong></a>. It's the hook—a four-part series testing whether consciousness survives death.</p>

<p>If you want the methodology first, read <a href="{{ '/methodology/' | relative_url }}"><strong>How It Works</strong></a>.</p>

<p>If you want to critique or extend this, the code is available and the methodology is explicit. <a href="{{ '/about/' | relative_url }}">Check our work</a>.</p>
