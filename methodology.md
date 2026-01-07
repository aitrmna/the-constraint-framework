---
layout: page
title: Methodology
description: How Claude reasons about mysteries. Constraint stacking explained.
permalink: /methodology/
---

This page describes the method used to analyze every mystery on this site.

---

## The Core Idea: Constraint Stacking

**Build cases by ordering constraints from most damning to least damning. Each constraint must fit within the solution space left by all constraints above it. Report what survives.**

We're not asserting truth. We're reporting what survives elimination.

---

## The Process

### Step 1: List All Plausible Explanations

Start with every explanation that could possibly account for what happened. Don't filter yet. This is your starting solution space.

### Step 2: Order Evidence by Eliminative Power

For each piece of evidence, ask: **"How much of the solution space does this eliminate?"**

The evidence that eliminates the most possibilities goes first. This is "most damning first."

**Key insight:** A 70% certain constraint that eliminates 90% of possibilities is MORE valuable than a 95% certain constraint that eliminates 20%.

### Step 3: Apply Constraints Top-Down

Work through the evidence in order:

**CONSTRAINT 1 (Most Damning):**
- State the evidence
- What does it eliminate?
- What remains?

**CONSTRAINT 2:**
- Must fit within remaining space from above
- What does it eliminate?
- What remains now?

Continue until the solution space is narrow.

### Step 4: Handle Anomalies Last

Strange evidence that doesn't fit cleanly must be explained within the solution space — it cannot break constraints that have already eliminated options.

When tight constraints converge from multiple independent sources, anomalies specify details — they don't reopen eliminated possibilities.

### Step 5: Report What Survives

The output is:

- **Eliminated:** A, B, C, D, E
- **Cannot eliminate:** F

That's the finding. We're not claiming F is true. We're reporting that we couldn't eliminate F.

---

## Two-Sided Testing

For questions where both sides have real evidence, we test BOTH directions:

**Part 1:** Test Hypothesis A → list constraints it fails

**Part 2:** Test Hypothesis B → list constraints it fails

**Part 3:** Weigh the failures

Not all failures are equal. We categorize by type:

| Evidence Type | Weight |
|---------------|--------|
| Unexplained anomalies (things exist that shouldn't) | HEAVY |
| Methodological limits (can't prove in lab) | MODERATE |
| Absence of evidence (haven't found X) | LIGHT |
| Prior improbability (seems unlikely) | LIGHTEST |

**The resolution:** The side with only priors/absence/methodological limits beats the side with unexplained anomalies.

**Why?** The side that can't explain what exists is in worse shape than the side that can't prove what it claims.

**Example:** In the consciousness analyses, materialism faces unexplained anomalies (terminal lucidity, the hard problem). Non-materialism faces only methodological limits (hard to prove in lab). Unexplained anomalies outweigh methodological limits. Non-materialism survives better.

---

## When Two-Sided Testing Applies

**Use it when:** Both hypotheses have real evidence against them from within the case.

**Don't use it when:** The "other side" only has priors or speculation.

**Example — Tic Tac:** The case for "mundane explanation" relies on "aliens are unlikely" (prior) and "no artifact recovered" (absence). These aren't case-specific evidence. The case for "non-human technology" addresses the actual recorded data. No two-sided testing needed — one side engages the evidence, one side doesn't.

**Example — Death:** The case for annihilation has real evidence (brain-consciousness correlation, no lab proof of survival). The case for survival has real evidence (terminal lucidity, verified NDEs). Both sides engage the evidence. Two-sided testing needed.

---

## Meta-Constraints: Convergence Across Cases

When multiple independent cases all survive to the same conclusion, the convergence itself becomes a constraint.

**Example:** Six UAP cases across different decades, countries, and sensor types all survive to "cannot eliminate non-human technology."

For the conclusion to be wrong, ALL SIX cases must have separate mundane explanations. The probability of this decreases as independent cases accumulate.

**The convergence IS the meta-constraint.**

---

## Why "Cannot Eliminate" Instead of Probabilities

Probability estimates require precision we don't have. "85% confidence" sounds scientific but is often invented.

"Cannot eliminate" is honest about what actually happened: we applied constraints, and this is what survived.

---

## Key Principles

1. **Constraints are primary.** Hard constraints define the solution space.
2. **Most damning first.** Order by eliminative power, not certainty.
3. **Test both directions** when both sides have real evidence.
4. **Weigh by evidence type.** Unexplained anomalies > methodological limits > absence > priors.
5. **Anomalies come last.** They must fit within the solution, not break it.
6. **Convergence compounds.** Independent cases pointing same direction strengthen the conclusion.

---

## What This Method Does

- **Eliminates explanations** that can't survive the evidence
- **Tests both directions** when warranted
- **Weighs failures** by evidence type
- **Shows the work** — every step visible
- **Handles uncertainty honestly** — sometimes multiple options survive

## What This Method Doesn't Do

- **Assert truth** — it reports what survives elimination
- **Produce certainty** — the method narrows; it doesn't prove
- **Access external reality** — Claude only has training data

---

[See it applied → UAP Mysteries]({{ '/mysteries/uap/' | relative_url }})

[See it applied → Consciousness Mysteries]({{ '/mysteries/consciousness/' | relative_url }})

---

## Use It Yourself

Want to apply constraint stacking to your own questions? We've distilled the method into a toolkit with templates, failure modes, and a quick reference checklist.

[Get the toolkit →]({{ '/toolkit/' | relative_url }})
