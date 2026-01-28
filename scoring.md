---
layout: page
title: Scoring System
description: How to quantify hypothesis strength
permalink: /scoring/
---

## Overview

The scoring system provides **objective, quantifiable comparison** between competing hypotheses.

Not claiming absolute truth. Showing **relative strength** based on how well predictions match reality.

---

## Basic Scoring Formula

### Success Rate

```
Success Rate = Confirmed Predictions / Total Predictions
```

**Simple ratio:**
- 10 predictions, 8 confirmed = 80% success rate
- 10 predictions, 3 confirmed = 30% success rate

---

## Severity Adjustment

**Not all failures are equal.** A hypothesis that fails a critical prediction is in worse shape than one that fails a minor "might" prediction.

### Failure Classifications

**MINOR failure (-):** 10% penalty
- Prediction was "possibly" or "might"
- Failure doesn't fundamentally undermine hypothesis
- Other factors could explain
- Example: "Might find fingerprints" → None found

**MAJOR failure (--):** 30% penalty
- Strong prediction that failed
- Central to hypothesis but alternatives exist
- Hard to explain away
- Example: "Should find animal reservoir within year" → None after 5 years

**CRITICAL failure (---):** 60% penalty
- Prediction was absolute necessity for hypothesis
- No alternative explanation
- Failure essentially proves hypothesis false
- Example: "Radar tracked actual objects" → Radar tracked F-16s tracking each other

### Severity Penalty Formula

```
Severity Penalty = (Minor Failures × 0.1) + (Major Failures × 0.3) + (Critical Failures × 0.6)
                   ─────────────────────────────────────────────────────────────────────────
                                         Total Predictions
```

---

## Overall Fit

```
Overall Fit = Success Rate × (1 - Severity Penalty)
```

**This is the final score for each hypothesis.**

---

## Worked Example

### Hypothesis: Belgian UFO Wave (Extraordinary Craft)

**Predictions:**

1. Radar tracked real objects → **CRITICAL FAIL** (tracked F-16s)
2. Visual confirmation by pilots → **CRITICAL FAIL** (pilots saw nothing)
3. Photos/videos exist → **CRITICAL FAIL** (one hoax photo only)
4. Contemporary media footage → **MAJOR FAIL** (essentially none found)
5. Reports on sighting date → **CRITICAL FAIL** (zero on date, 143 after publicity)

**Scoring:**
- Total predictions: 5
- Confirmed: 0
- Minor failures: 0
- Major failures: 1
- Critical failures: 4

**Success Rate:** 0/5 = 0%

**Severity Penalty:** 
- (0 × 0.1) + (1 × 0.3) + (4 × 0.6) / 5
- 0 + 0.3 + 2.4 / 5
- 2.7 / 5 = 0.54 = 54%

**Overall Fit:** 0% × (1 - 0.54) = **0%**

**Result:** Hypothesis essentially disproven.

---

## Interpretation Scale

| Overall Fit | Interpretation | Confidence |
|------------|----------------|------------|
| 90-100% | Overwhelming support | Near certainty |
| 70-89% | Strong support | High confidence |
| 50-69% | Moderate support | Probable |
| 30-49% | Weak support | Possible but unlikely |
| 10-29% | Very weak support | Improbable |
| 0-9% | Essentially disproven | Reject hypothesis |

---

## Comparing Hypotheses

### Advantage Ratio

```
Advantage Ratio = Best Hypothesis Overall Fit / Next Best Overall Fit
```

**Interpretation:**

| Ratio | Meaning | Confidence |
|-------|---------|------------|
| 100:1+ | Overwhelming winner | Alternative essentially impossible |
| 20:1 to 99:1 | Very strong winner | Alternatives highly improbable |
| 10:1 to 19:1 | Strong winner | Alternatives unlikely |
| 5:1 to 9:1 | Moderate winner | Alternatives possible but less likely |
| 2:1 to 4:1 | Weak winner | Alternatives remain plausible |
| <2:1 | Too close to call | Evidence insufficient |

---

## Real Examples

### COVID Origin

| Hypothesis | Predictions | Confirmed | Failed (severity) | Success Rate | Penalty | Overall Fit |
|-----------|-------------|-----------|-------------------|--------------|---------|-------------|
| **Lab Leak** | 8 | 8 | 0 | 100% | 0% | **100%** |
| Natural Origin | 8 | 0 | 8 (all major/critical) | 0% | 75% | **0.75%** |

**Advantage Ratio:** 100% / 0.75% = **133:1 for lab leak**

---

### JonBenét Ramsey

| Hypothesis | Overall Fit |
|-----------|-------------|
| **Burke + Parent Cover-up** | **100%** |
| Patsy Rage Killing | 26% |
| John Sexual Abuse | 15% |
| Failed Kidnapping | 8% |
| Stranger Intruder | 0.5% |

**Advantage Ratios:**
- Burke vs Patsy: 100% / 26% = **3.8:1** (weak to moderate)
- Burke vs Intruder: 100% / 0.5% = **200:1** (overwhelming)

---

### Tic Tac UAP

| Hypothesis | Predictions | Overall Fit |
|-----------|-------------|-------------|
| **Non-Human Technology** | 10 | **60%** |
| Secret US Tech | 8 | 5% |
| Foreign Tech | 8 | 2% |
| Natural Phenomenon | 10 | 1% |
| Sensor Malfunction | 8 | 0.5% |

**Advantage Ratio:** 60% / 5% = **12:1 for non-human tech**

*Note: Score isn't 100% due to some unclear predictions and one-horn detection issue (equipment-related uncertainty)*

---

## Key Principles for Scoring

### 1. Generate Predictions First

Don't look at evidence then create predictions to match.

**Process:**
1. Write down ALL predictions for a hypothesis
2. Lock them in
3. THEN check against evidence

**This prevents post-hoc rationalization.**

### 2. Be Honest About Failures

Don't ignore or downplay failed predictions.

**Every failed prediction counts.**

Severity ratings should reflect actual importance to hypothesis, not desired outcome.

### 3. Classify Severity Objectively

**Ask these questions:**

**For MINOR:**
- Was prediction weak ("might," "possibly")?
- Can hypothesis survive without this?
- Are alternative explanations available?

**For MAJOR:**
- Was prediction strong and specific?
- Is it central to hypothesis?
- Is failure hard to explain?

**For CRITICAL:**
- Was prediction absolute necessity?
- Does failure prove hypothesis false?
- Is there NO alternative explanation?

### 4. Count Everything

**Include in total predictions:**
- ✓ Passes
- ✗ Failures (all severities)
- ⚠️ Unclear (count as 0.5 pass when calculating)

**Don't selectively count only favorable predictions.**

### 5. Use Scores for Comparison

Scores show **relative strength**, not absolute truth.

**85% doesn't mean "85% certain it's true."**

It means: "This hypothesis fits evidence much better than alternatives."

---

## Handling Edge Cases

### What if all hypotheses score low?

**Possible interpretations:**
1. Evidence is insufficient
2. True hypothesis not yet considered
3. Predictions too strict
4. Mystery genuinely unresolvable with current data

**Action:** Report that no hypothesis survives well. Don't force a winner.

### What if two hypotheses score similarly?

**Example:** 
- H1: 68%
- H2: 65%

**Advantage ratio:** 68% / 65% = 1.05:1

**Interpretation:** Too close to call. Evidence insufficient to differentiate.

**Action:** Report both as viable. Identify what evidence would differentiate them.

### What about unclear predictions?

**When evidence is ambiguous:**

Count as 0.5 for success rate calculation.

**Example:**
- 10 predictions
- 6 confirmed
- 2 failed
- 2 unclear

**Success rate:** (6 + 1) / 10 = 70%

### What if new evidence emerges?

**Re-score with new evidence.**

Framework should be **dynamic**, not static.

Good hypotheses welcome new evidence. Bad hypotheses fail under additional scrutiny.

---

## Self-Check Questions

Before finalizing scores, ask:

1. **Did I generate predictions before checking evidence?**
   - If no → risk of post-hoc rationalization

2. **Am I counting all predictions, including failures?**
   - If no → risk of cherry-picking

3. **Are severity ratings justified?**
   - Can I explain why critical vs major vs minor?

4. **Would someone who disagrees with my conclusion accept my scoring logic?**
   - If no → review for bias

5. **Am I using scores for comparison or claiming absolute truth?**
   - Scores show relative strength only

---

## Common Scoring Mistakes

### Mistake 1: Vague predictions that can't fail

**Bad:** "Something unusual might be observed"
**Good:** "Object should accelerate >100g without sonic boom"

**Why it matters:** Vague predictions always "pass" but provide no information.

### Mistake 2: Post-hoc severity assignment

**Bad:** Prediction fails → "Well, that was only minor anyway"
**Good:** Assign severity BEFORE checking → stick to it

### Mistake 3: Treating 90% as certainty

**Bad:** "90% score means we know it's true"
**Good:** "90% score means this hypothesis fits much better than alternatives, but new evidence could change this"

### Mistake 4: Ignoring base rates

**Bad:** Treating 10:1 advantage as decisive for extremely unlikely prior hypothesis
**Good:** Consider prior probability. 10:1 evidence favoring 1-in-1000 prior = still unlikely overall

### Mistake 5: False precision

**Bad:** "Hypothesis is 73.2% likely"
**Good:** "Hypothesis scores in strong support range (70-89%)"

Round to meaningful categories. Don't over-specify.

---

## Advanced: Bayesian Integration

Scores can feed into Bayesian updating:

```
Posterior Odds = Prior Odds × Likelihood Ratio

Where Likelihood Ratio ≈ (Overall Fit of H1) / (Overall Fit of H2)
```

**Example:**

**Prior odds:** Lab leak vs natural = 1:1 (50/50 before evidence)
**Evidence (scoring):** Lab leak 100%, Natural 0.75%
**Likelihood ratio:** 100 / 0.75 = 133:1

**Posterior odds:** 1:1 × 133:1 = **133:1 for lab leak**

**Posterior probability:** 133/134 = **99.3% for lab leak**

---

## Scoring Template

```
HYPOTHESIS: [Name]

PREDICTIONS:
1. [Prediction] → [PASS/FAIL/UNCLEAR] [Severity if fail: -/--/---]
2. [Prediction] → [PASS/FAIL/UNCLEAR] [Severity if fail: -/--/---]
3. [Prediction] → [PASS/FAIL/UNCLEAR] [Severity if fail: -/--/---]
...

TOTALS:
- Total predictions: ___
- Confirmed: ___
- Failed (minor): ___
- Failed (major): ___
- Failed (critical): ___
- Unclear: ___

CALCULATION:
Success Rate = ___ / ___ = ___%

Severity Penalty = (__ × 0.1 + __ × 0.3 + __ × 0.6) / __ = ___%

Overall Fit = ___% × (1 - ___%) = ___%

INTERPRETATION: [Overwhelming/Strong/Moderate/Weak/Very Weak/Disproven]
```

---

## Next Steps

**See scoring applied to real cases:**
<p><a href="{{ '/mysteries/' | relative_url }}">Case studies →</a></p>

**Understand the full methodology:**
<p><a href="{{ '/methodology/' | relative_url }}">Complete framework →</a></p>

**Quick-start guide:**
<p><a href="{{ '/start/' | relative_url }}">When and how to use →</a></p>

---

## Remember

**The framework doesn't produce truth. It produces honest comparison.**

It forces you to:
- List predictions before checking
- Count failures honestly
- Weight severity objectively
- Compare fairly
- State confidence accurately

That's the value. Not certainty. **Intellectual honesty.**
