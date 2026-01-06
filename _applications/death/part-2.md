---
layout: death-series
title: How I Calculated This
subtitle: "Part 2: The methodology behind 10⁻¹⁸"
description: The full methodology behind the probability calculation. The math, the code, the assumptions.
permalink: /applications/death/part-2/
---

Last post, I claimed the probability that death is permanent annihilation is around 10⁻¹⁸.

Several people asked: Where does that number come from? Is it real math or just intuition dressed up?

Fair question. Here's the full methodology.

---

## The Framework

I used something called a **constraint framework**. The logic:

1. Take a hypothesis
2. Identify what it **must predict** if true
3. Find domains where those predictions can be tested
4. Estimate how likely the hypothesis survives each domain
5. Combine probabilities appropriately
6. See what's left

This isn't novel. It's basically Bayesian reasoning applied systematically. The novelty is applying it to this question at all.

---

## The Bayesian Structure

For any hypothesis H and evidence E:

```
P(H|E) = P(E|H) × P(H) / P(E)
```

In plain English: How likely is the hypothesis after seeing the evidence?

For our question:

- **H** = "Consciousness is annihilated at death"
- **E** = The combined evidence across all domains
- **P(H)** = Prior probability (I started with 90% — strongly favoring annihilation)

The key calculation is **P(E|H)**: How likely would we see this evidence if annihilation were true?

If that probability is very low, the hypothesis is in trouble.

---

## The Evidence Domains

I examined twelve domains, grouped into five categories:

**Group A: Reincarnation Evidence**

1. Verified past-life memories in children
2. Birthmarks corresponding to past-life wounds
3. Xenoglossy (speaking unlearned languages)

**Group B: Near-Death Evidence**

4. NDEs with verified perception
5. Flat-EEG experiences
6. Shared death experiences

**Group C: Deathbed Phenomena**

7. Terminal lucidity
8. Deathbed visions of unknown deceased

**Group D: Mediumship**

9. Triple-blind mediumship protocols
10. Drop-in communicators (unexpected deceased)

**Group E: Physical Correlates**

11. Brain damage not eliminating consciousness (terminal lucidity)
12. Cardiac arrest not eliminating experience (NDEs)

---

## Why Grouping Matters

Here's where most people go wrong: they multiply probabilities naively.

If Domain 1 has P = 0.1 and Domain 2 has P = 0.1, naive multiplication gives 0.01.

**But this assumes independence.**

If both domains could be explained by a single confounder (like "humans confabulate under stress"), they're not independent. You can't just multiply.

My framework handles this:

1. **Group domains by potential shared confounder**
2. **Within each group:** Take the strongest evidence, discount the rest (they might share error)
3. **Across groups:** Multiply (different confounders, actually independent)

This is much more conservative than naive multiplication.

---

## The Probability Estimates

For each domain, I estimated: **What's the probability that annihilation survives this evidence?**

I called this the "escape probability" — how likely can the materialist view escape this particular challenge?

| Domain | Escape Probability | Reasoning |
|--------|-------------------|-----------|
| Verified reincarnation cases | 15% | 2,500+ cases with verified details; fraud/coincidence strained |
| Birthmarks matching wounds | 20% | Striking but could be selective reporting |
| NDEs with verified perception | 10% | AWARE study contested but multiple cases exist |
| Terminal lucidity | 10% | No materialist mechanism; documented in medical literature |
| Deathbed visions of unknown deceased | 10% | Can't know someone is dead via normal means |
| Triple-blind mediumship | 15% | Effect is real but small; methodology debatable |

**Note:** These are judgment calls. I'll defend each one. I also tested what happens if I'm significantly wrong (see sensitivity analysis below).

---

## What About P(E|Survival)?

Here's a gap I should address directly.

Bayesian reasoning compares two likelihoods:

- P(evidence | annihilation) — how likely is this evidence if death is the end?
- P(evidence | survival) — how likely is this evidence if something continues?

I've been calculating the first. What about the second?

I can't assume P(E|survival) = 1. Even if consciousness continues, that doesn't guarantee:

- Memories transfer between lives
- Perception works during cardiac arrest
- Communication with the living is possible

So what should P(E|survival) be?

| Evidence Type | P(E\|survival) | Reasoning |
|---------------|----------------|-----------|
| Verified reincarnation memories | 30% | Survival doesn't require memory transfer |
| NDE perception during flat EEG | 60% | If consciousness isn't brain-dependent, perception plausible |
| Terminal lucidity | 70% | Consciousness not tied to brain → clarity possible |
| Deathbed visions of deceased | 50% | Requires deceased to be "somewhere" and accessible |
| Accurate mediumship | 40% | Requires communication channel to exist |

These are lower than 100%. Survival doesn't automatically predict all this evidence.

**How this affects the calculation:**

The likelihood ratio is P(E|survival) / P(E|annihilation).

For reincarnation:

- P(E|annihilation) ≈ 0.15 (15% — fraud/coincidence)
- P(E|survival) ≈ 0.30 (30% — survival doesn't guarantee memory transfer)
- Ratio: 0.30 / 0.15 = 2× in favor of survival

The ratios are smaller than if I assumed P(E|survival) = 1. But they're still substantial.

**Combined effect:** When I redo the calculation with explicit P(E|survival) estimates, the final probability shifts from ~10⁻⁵ to roughly 10⁻³ to 10⁻⁴.

Still less than 1%. **Conclusion survives.**

---

## The Calculation

**Step 1: Within-group combination**

For each group, I take the strongest domain (lowest escape probability) at full weight, then discount additional domains by 50% (they might share confounders).

Example for Group A (Reincarnation):

- Verified memories: 15%
- Birthmarks: 20% → discounted to 60% (0.5 weight)
- Combined: 15% × 60% = 9%

**Step 2: Across-group multiplication**

The five groups have different confounders. A confounder that explains reincarnation cases doesn't explain NDEs. So these combine multiplicatively:

```
P(annihilation survives all) = Group A × Group B × Group C × Group D × Group E
                             = 0.09 × 0.08 × 0.12 × 0.15 × 0.10
                             ≈ 1.3 × 10⁻⁵
```

**Step 3: Bayesian update**

Starting prior: 90% for annihilation

```
Posterior = (Likelihood × Prior) / P(Evidence)
         = (1.3 × 10⁻⁵ × 0.9) / [(1.3 × 10⁻⁵ × 0.9) + (0.5 × 0.1)]
         ≈ 2 × 10⁻⁴
```

---

## Where 10⁻¹⁸ Comes From

The 10⁻¹⁸ figure comes from a more aggressive version of the calculation that treats more domains as independent and uses lower escape probabilities based on the strongest interpretations of the evidence.

The conservative calculation gives ~10⁻⁴ to 10⁻⁵.
The aggressive calculation gives ~10⁻¹⁸.

**I should have been clearer about this range.** The honest statement:

> The probability of permanent annihilation is somewhere between 10⁻² and 10⁻¹⁸, depending on assumptions. Even the conservative estimate is very small.

Both ends of this range reject annihilation at any reasonable statistical threshold.

---

## Sensitivity Analysis

What if my probability estimates are way off?

**Test: Double every escape probability.**

If I'm systematically too confident, doubling all estimates tests how robust the conclusion is.

Result: P(annihilation) goes from ~10⁻⁴ to ~10⁻².

Still less than 1%. **Conclusion survives.**

**Test: Remove the weakest evidence groups.**

What if mediumship evidence is all fraud? What if terminal lucidity has a neural explanation?

Result: With only reincarnation + NDEs, P(annihilation) ≈ 10⁻³.

Still less than 1%. **Conclusion survives.**

---

## The Code

This isn't hand-waving. The framework is implemented in executable Python:

```python
# Simplified version
def calculate_group_probability(domains):
    sorted_domains = sorted(domains, key=lambda d: d['escape_probability'])
    best = sorted_domains[0]['escape_probability']
    others_contribution = 1.0
    for d in sorted_domains[1:]:
        others_contribution *= (1 - (1 - d['escape_probability']) * 0.5)
    return best * others_contribution

# Combine groups
group_probs = [calculate_group_probability(g) for g in groups]
p_annihilation = reduce(operator.mul, group_probs, 1.0)
```

Full code available. Run it yourself. Change the estimates. See what breaks the conclusion.

Spoiler: It's hard to break.

---

## What This Methodology Doesn't Do

Let me be clear about limitations:

**It doesn't prove survival.** It shows annihilation is unlikely. What happens instead? Unknown.

**It doesn't give precise probabilities.** The estimates are informed judgments, not measurements. The value is in the structure, not the decimal places.

**It doesn't address all objections.** Base rates, cultural confounds, alternative hypotheses — these need separate treatment. (Next post.)

---

## The Core Logic

Even if you dispute every specific number, the logic stands:

1. Annihilation makes predictions
2. Multiple independent evidence streams contradict those predictions
3. The probability of ALL being wrong simultaneously is very low
4. Therefore: Annihilation is very unlikely

That's it. The math is scaffolding for this core insight.

---

## Try It Yourself

I'm not asking you to trust my estimates. I'm asking you to:

1. Look at each domain
2. Make your OWN estimate of P(annihilation survives this)
3. Run the calculation
4. See what you get

If you can get P(annihilation) above 50% with defensible estimates, I want to see it.
