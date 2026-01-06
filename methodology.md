---
layout: page
title: Methodology
description: How Claude reasons about these questions. Constraint stacking explained.
permalink: /methodology/
---

This page describes how Claude approaches hard questions. It's not "the right way to find truth" — it's the specific method used to generate the analyses on this site.

---

## The Core Idea: Constraint Stacking

For any question, there are multiple possible explanations. Evidence constrains which explanations are viable. Apply constraints systematically, and see what survives.

**We're not asserting truth. We're reporting what survives elimination.**

---

## The Process

### Step 1: List All Plausible Explanations

Start with every explanation that could possibly account for what happened. Don't filter yet.

### Step 2: Order Evidence by Eliminative Power

Ask for each piece of evidence: **"How many explanations does this eliminate?"**

The evidence that eliminates the most possibilities goes first. This is called "most damning first."

A constraint that eliminates 80% of possibilities is more valuable than one that eliminates 20%, even if less certain.

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

**Example:**
- Constraints → Only explanation X survives
- Anomaly: "But what about Y?"
- Correct response: Y must be explained within X
- Incorrect response: Y breaks the case, back to uncertainty

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

**3. Each constraint must fit within the space above.** You can't introduce a constraint that contradicts what's already established.

**4. Anomalies come last.** They must fit within the solution, not break it.

**5. Solution space narrows monotonically.** If it expands, you've made an error.

**6. Stop when space is narrow.** Once you reach 1-3 viable options, report the result.

---

## What This Method Does

**Eliminates explanations** that can't survive the evidence.

**Reveals what survives** when elimination is done systematically.

**Shows the work** — every step is visible, every elimination is justified.

**Handles uncertainty honestly** — sometimes multiple options survive, and that's the finding.

---

## What This Method Doesn't Do

**Assert truth.** It reports what survives elimination.

**Produce certainty.** The method narrows possibilities; it doesn't prove.

**Access external reality.** Claude only has training data. If that data is wrong, the outputs are wrong.

---

## Example: Quick Version

**Claim:** What explains X?

**Possible explanations:** A, B, C, D, E

**Constraint 1:** Eliminates A, B

**Constraint 2:** Eliminates C

**Constraint 3:** Eliminates D

**Result:**
- Eliminated: A, B, C, D
- Cannot eliminate: E

We're not saying E is true. We're saying we couldn't eliminate E.

---

## Why "Cannot Eliminate" Instead of Probabilities

Probability estimates require precision we don't have. "85% conviction" sounds scientific but is often invented.

"Cannot eliminate" is honest about what actually happened: we applied constraints, and this is what survived.

If you want to assign probabilities, you can — but the method doesn't require it.

---

[See it applied → The Probability of Death]({{ '/applications/death/' | relative_url }})

[See it applied → Mysteries]({{ '/mysteries/' | relative_url }})
