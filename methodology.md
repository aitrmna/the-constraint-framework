---
layout: page
title: Methodology
description: The seven-step methodology for testing beliefs against evidence using systematic Bayesian reasoning.
permalink: /methodology/
---

A systematic approach to testing beliefs against evidence. The framework applies Bayesian reasoning across multiple independent evidence domains to determine which hypotheses survive contact with reality.

---

## Core Principle

Most contested questions get stuck in intuition vs. intuition. The constraint framework asks:

> What would have to be true if this hypothesis were correct?
> Can we find domains where we can test that?
> Does the hypothesis survive?

A hypothesis that fails across multiple independent domains is probably wrong—even if it feels right.

---

## The Seven Steps

### 1. Define the Hypothesis

State the claim being tested as precisely as possible. Vague hypotheses can't be tested.

**Example:** "Consciousness is permanently annihilated at biological death"

### 2. Identify Required Predictions

What *must* be true if the hypothesis is correct? These aren't arbitrary tests—they're logical requirements.

**Example:** If consciousness ends at death, then:

- No verified memories should transfer between lives
- No accurate perception should occur during cardiac arrest
- No information should be accessible from the deceased

### 3. Find Evidence Domains

Locate empirical areas where these predictions can be tested. Look for:

- Published research
- Replicated findings
- Verified cases
- Systematic documentation

### 4. Estimate Escape Probabilities

For each domain, estimate: **What's the probability the hypothesis survives this evidence?**

This is a judgment call—but structured judgment. You must:

- Assign an actual number (forces consistency)
- Defend it (forces rigor)
- Test it (sensitivity analysis)

### 5. Group by Potential Confounders

Which domains might share a common error? Don't naively multiply probabilities for domains that could fail together.

**Example groups:**

- Reincarnation evidence (might share cultural confounds)
- NDE evidence (might share brain-state confounds)
- Mediumship evidence (might share fraud/cold-reading confounds)

### 6. Combine Appropriately

**Within groups:** Take strongest domain at full weight, discount others by 50%

**Across groups:** Multiply (different confounders = actually independent)

### 7. Apply Bayesian Update

```
P(H|E) = P(E|H) × P(H) / P(E)

where:
  P(H|E) = posterior probability of hypothesis
  P(E|H) = likelihood of evidence given hypothesis
  P(H) = prior probability
  P(E) = total probability of evidence
```

---

## Key Methodological Choices

### Why Grouping Matters

Naive multiplication assumes independence. If Domain 1 and Domain 2 could both be explained by "humans confabulate," they're not independent. Grouping prevents overconfidence.

### Why Explicit P(E|Alternative) Matters

Bayes requires comparing two likelihoods. If the alternative hypothesis also predicts the evidence weakly, the likelihood ratio shrinks.

### Why Sensitivity Analysis Matters

Individual probability estimates are judgment calls. Testing whether the conclusion survives doubled probabilities (or removed domains) shows robustness.

---

## Example Calculation

```python
# Python implementation
import operator
from functools import reduce

def calculate_group_probability(domains):
    sorted_domains = sorted(domains, key=lambda d: d['escape_prob'])
    best = sorted_domains[0]['escape_prob']
    others = 1.0
    for d in sorted_domains[1:]:
        others *= (1 - (1 - d['escape_prob']) * 0.5)
    return best * others

groups = [
    [{'name': 'Reincarnation', 'escape_prob': 0.15}],
    [{'name': 'NDEs', 'escape_prob': 0.10}],
    [{'name': 'Terminal lucidity', 'escape_prob': 0.10}],
    [{'name': 'Mediumship', 'escape_prob': 0.15}],
]

group_probs = [calculate_group_probability(g) for g in groups]
p_survives = reduce(operator.mul, group_probs, 1.0)

print(f"P(hypothesis survives): {p_survives:.2e}")
```

---

## Limitations

- Probability estimates are informed judgments, not measurements
- Correlation structure is approximate
- Some evidence domains have uncertain base rates
- The framework constrains what's NOT true more than what IS true
- Results should update, not crystallize

---

## When To Use This

**Good for:**

- Questions with multiple evidence domains
- Contested hypotheses with available data
- Topics where intuitions differ
- Making uncertainty explicit

**Not for:**

- Questions with no testable predictions
- Purely definitional disputes
- Topics with no evidence base

---

[See the framework applied → The Probability of Death]({{ '/applications/death/' | relative_url }})
