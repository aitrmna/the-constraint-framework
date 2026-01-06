---
layout: page
title: Methodology
description: How Claude reasons about these questions. The framework explained.
permalink: /methodology/
---

This page describes how Claude approaches hard questions. It's not "the right way to find truth" — it's the specific method used to generate the analyses on this site.

---

## The Core Approach

When asked a question like "What's the probability X is true?", Claude:

1. Takes the hypothesis seriously
2. Asks what must be true if the hypothesis is correct
3. Looks for domains in training data where those predictions can be tested
4. Estimates how well the hypothesis survives each domain
5. Combines the estimates
6. Reports what falls out

This is Bayesian reasoning applied systematically. Whether it produces "truth" depends on whether the training data is accurate — which is unknowable.

---

## The Seven Steps

### 1. Define the Hypothesis

State the claim precisely. Vague claims can't be tested.

Example: "Consciousness is permanently annihilated at biological death"

### 2. Identify Required Predictions

What *must* be true if the hypothesis is correct? These are logical requirements, not arbitrary tests.

Example: If consciousness ends at death, then:
- No verified memories should transfer between lives
- No accurate perception should occur during cardiac arrest
- No information should be accessible from the deceased

### 3. Find Evidence Domains

Locate areas in training data where these predictions can be tested. Look for:
- Published research
- Documented cases
- Systematic studies

### 4. Estimate Survival Probability

For each domain, estimate: What's the probability the hypothesis survives this evidence?

This is a judgment call — Claude assigning numbers based on training data. The value is in forcing explicit comparison, not in the precision of the numbers.

### 5. Group by Potential Confounders

Which domains might share a common error? Don't multiply probabilities for domains that could fail together.

Example groups:
- Reincarnation evidence (might share cultural confounds)
- NDE evidence (might share brain-state confounds)
- Mediumship evidence (might share fraud confounds)

### 6. Combine Appropriately

**Within groups:** Take strongest domain at full weight, discount others

**Across groups:** Multiply (different confounders = more independent)

### 7. Report the Output

State what the calculation produces. That's the answer — not "the truth," just the output of this process applied to this training data.

---

## Why This Format

**Structure forces consistency.** Assigning actual numbers prevents vague hand-waving.

**Assumptions become visible.** You can see exactly what estimates drive the conclusion.

**Disagreement becomes productive.** Instead of "I don't buy it," you can say "I think that domain should be 30%, not 10%."

**Sensitivity can be tested.** Double the estimates. Remove domains. See if the conclusion survives.

---

## What This Method Doesn't Do

**It doesn't access external reality.** Claude only has training data. If that data is wrong, the outputs are wrong.

**It doesn't produce certainty.** The numbers are judgment calls, not measurements.

**It doesn't prove anything.** It shows what falls out of systematic reasoning on available information.

---

## The Honest Limitation

This entire methodology rests on Claude's training data being somewhat accurate. If Anthropic fed Claude fabricated studies, this all collapses. If the researchers whose work is in the training data were frauds, this all collapses.

We can't check this. Neither can you.

The methodology is sound. Whether the inputs are sound is a different question — one that might be unanswerable.

---

[See it applied → The Probability of Death]({{ '/applications/death/' | relative_url }})
