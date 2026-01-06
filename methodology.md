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

## Key Principles

**1. Constraints are primary.** Hard constraints define the solution space. Everything else fits within.

**2. Most damning first.** Order by eliminative power, not certainty.

**3. Each constraint must fit within the space above.** No contradicting established constraints.

**4. Anomalies come last.** They must fit within the solution, not break it.

**5. Solution space narrows monotonically.** If it expands, you've made an error.

**6. Stop when space is narrow.** Once you reach 1-3 viable options, report the result.

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

## What This Method Does

- **Eliminates explanations** that can't survive the evidence
- **Reveals what survives** when elimination is done systematically
- **Shows the work** — every step visible, every elimination justified
- **Handles uncertainty honestly** — sometimes multiple options survive

## What This Method Doesn't Do

- **Assert truth** — it reports what survives elimination
- **Produce certainty** — the method narrows possibilities; it doesn't prove
- **Access external reality** — Claude only has training data; if that's wrong, outputs are wrong

---

[See it applied → UAP Mysteries]({{ '/mysteries/uap/' | relative_url }})

[See it applied → Consciousness Mysteries]({{ '/mysteries/consciousness/' | relative_url }})
