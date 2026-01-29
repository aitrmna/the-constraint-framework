---
layout: page
title: Scoring System
description: How to quantify hypothesis strength
permalink: /scoring/
---

## The Formula

```
Score = Success Rate × (1 - Severity Penalty)
```

**That's it.**

### Success Rate
```
Success Rate = Passes / Total Predictions
```

### Severity Penalty
```
Severity Penalty = (Minor×0.1 + Major×0.3 + Critical×0.6) / Total
```

### Failure Classifications

**MINOR (-):** 10% penalty each
- Weak predictions ("might", "possibly")
- Doesn't fundamentally damage hypothesis
- Example: "Might find fingerprints" → None found

**MAJOR (--):** 30% penalty each
- Strong predictions that failed
- Central to hypothesis, hard to explain
- Example: "Should find animal reservoir within year" → None after 5 years

**CRITICAL (---):** 60% penalty each
- Absolute necessities
- No alternative explanation
- Example: "Radar tracked objects" → Tracked F-16s tracking each other

**Critical failures kill the hypothesis.** One black swan proves "all swans are white" is false.

---

## Worked Example: Belgian UFO Wave

**Claim:** Extraordinary craft over Belgium

**Predictions:**
1. Radar tracked real objects → **CRITICAL FAIL**
2. Pilots visually confirmed → **CRITICAL FAIL**
3. Photos/video exist → **CRITICAL FAIL**
4. Contemporary footage → **MAJOR FAIL**
5. Reports on sighting date → **CRITICAL FAIL**

**Calculation:**
- Total: 5
- Passes: 0
- Critical failures: 4
- Major failures: 1

Success Rate = 0/5 = 0%
Severity Penalty = (0.3 + 2.4)/5 = 54%
Score = 0% × (1 - 0.54) = **0%**

**Result:** Dead. Multiple critical failures.

---

## Interpretation Scale

| Score | Meaning |
|-------|---------|
| 90-100% | Overwhelming support |
| 70-89% | Strong support |
| 50-69% | Moderate support |
| 30-49% | Weak support |
| 10-29% | Very weak support |
| 0-9% | Essentially disproven |

**Any critical failures → 0% regardless of passes.**

One counterexample kills the hypothesis. That's how falsification works.

---

## Scoring Surviving Hypotheses

**A hypothesis can survive (zero critical failures) but still score low.**

### Example: Tic Tac Non-Human Technology

**Predictions:**
1. Trans-medium capability → **PASS** (water to air)
2. Instantaneous acceleration → **PASS** (multiple witnesses)
3. No visible propulsion → **PASS** (all observers)
4. Radar + visual + FLIR → **PASS** (independent confirmation)
5. Trained observers → **PASS** (Navy pilots)
6. Jams radar systems → **MINOR FAIL** (AEGIS worked fine)
7. Multiple simultaneous sensors → **PASS** (Princeton radar + aircraft)
8. Repeatable observations → **PASS** (multiple days, multiple craft)
9. Physics-defying performance → **PASS** (no sonic boom at speed)
10. No infrared signature → **MINOR FAIL** (FLIR detected it)

**Calculation:**
- Total: 10
- Passes: 8
- Minor failures: 2
- Major failures: 0
- Critical failures: 0

Success Rate = 8/10 = 80%
Severity Penalty = (2×0.1)/10 = 2%
Score = 80% × (1 - 0.02) = **78.4%**

**Result:** Survives with strong support. Minor issues with sensor behavior don't kill it.

### Compare to Alternatives

**Weather Balloon:**
- Score: 0% (critical failures: can't hover, can't accelerate, can't go underwater)

**Secret US Tech:**
- Score: ~15% (major failures: testing over carrier group, risking pilots, no deployment)

**Sensor Malfunction:**
- Score: 0% (critical failure: multiple independent sensors + visual)

**Winner:** Non-human tech at 78%. Not perfect, but only one without critical failures.

---

## Comparing Hypotheses

```
Advantage Ratio = Best Score / Next Best Score
```

**Interpretation:**

| Ratio | Meaning |
|-------|---------|
| 100:1+ | Alternative essentially impossible |
| 20:1 to 99:1 | Alternative highly improbable |
| 10:1 to 19:1 | Alternative unlikely |
| 5:1 to 9:1 | Alternative possible but less likely |
| 2:1 to 4:1 | Close call |
| <2:1 | Too close to call |

**Example:**
- Non-human tech: 78%
- Secret tech: 15%
- Ratio: 5.2:1 (moderate advantage)

**Example:**
- Lab leak: 100%
- Natural origin: 0.75%
- Ratio: 133:1 (overwhelming)

---

## The Critical Distinction

**Score measures two things:**

1. **Survival:** Does it avoid critical failures? (YES/NO)
2. **Quality:** How well does it fit? (0-100%)

**A hypothesis must pass #1 to be viable. #2 ranks the survivors.**

---

## Real Examples

### COVID Origin

| Hypothesis | Passes | Fails (Severity) | Score |
|-----------|---------|------------------|-------|
| Lab Leak | 8 | 0 | **100%** |
| Natural Origin | 0 | 8 (major/critical) | **0.75%** |

Advantage: 133:1 for lab leak

### JonBenét Ramsey

| Hypothesis | Score |
|-----------|-------|
| Burke + Cover-up | **100%** |
| Patsy Rage | 26% |
| John Abuse | 15% |
| Intruder | 0.5% |

Advantage: 3.8:1 vs Patsy, 200:1 vs Intruder

### D.B. Cooper

| Hypothesis | Score |
|-----------|-------|
| Died | **95%** |
| Survived | 1% |

Advantage: 95:1 for death

---

## Where Uncertainty Lives

**Not in the formula. In the evidence.**

The math is mechanical:
```
Score = Success Rate × (1 - Severity Penalty)
```

The judgment is in classification:

**Is this a critical failure?**
- Belgian radar data (official report) → YES, critical
- Anecdotal "seemed weird" → NO, insufficient quality

**Is this a pass?**
- Lab leak: 80,000 animals tested, no reservoir → YES, high quality
- "Someone said they found it" → NO, unverified

**Garbage in, garbage out.** The scoring is only as good as your evidence classification.

---

## Common Mistakes

**1. Ignoring critical failures**
- "Yeah but look at all these passes"
- One black swan kills "all swans are white"
- Critical failures → 0% regardless

**2. False precision**
- "73.4% likely"
- Round to brackets: strong support, moderate support, etc.

**3. Treating scores as certainty**
- "90% means it's true"
- NO: 90% means "fits evidence much better than alternatives"
- Evidence could be wrong or incomplete

**4. Weak evidence classification**
- Counting unverified claims as passes
- Treating minor issues as critical failures
- The quality of your scoring depends on quality of classification

**5. Not scoring all hypotheses**
- Only checking your preferred answer
- Score ALL serious hypotheses, compare numerically

---

## The Process

1. List all serious hypotheses
2. For each: Generate predictions (what must be true?)
3. Classify evidence: PASS/FAIL/UNCLEAR, severity if fail
4. Calculate scores
5. Compare

**Highest scoring hypothesis with zero critical failures wins.**

---

## Key Principles

**One counterexample kills:**
- Critical failures → 0% immediately
- No confidence factor, no second chances
- That's falsification

**Score measures fit quality:**
- How many predictions pass?
- How severe are the failures?
- Mechanical calculation once evidence is classified

**Uncertainty lives in evidence:**
- Is this really a critical failure?
- Is this evidence high quality?
- That's where judgment happens

---

## Template

```
HYPOTHESIS: [Name]

PREDICTIONS:
1. [Prediction] → PASS/FAIL (severity: -/--/---)
2. [Prediction] → PASS/FAIL (severity: -/--/---)
...

TOTALS:
Total: ___
Passes: ___
Minor fails: ___
Major fails: ___
Critical fails: ___

CALCULATION:
Success Rate = ___ / ___ = ___%
Severity Penalty = (___ × 0.1 + ___ × 0.3 + ___ × 0.6) / ___ = ___%
Score = ___% × (1 - ___%) = ___%

INTERPRETATION: [Support level]
```

---

<p><a href="{{ '/methodology/' | relative_url }}">Complete methodology →</a></p>
<p><a href="{{ '/mysteries/' | relative_url }}">Case studies →</a></p>
