# When Ownership Shapes Care  
## Performance and Variability Inside Nursing Home Chains

### Overview

If two nursing homes operate under the same regulations, funding structures, and reporting requirements, why do patient outcomes diverge so sharply once ownership and scale enter the picture?

As consolidation accelerates across long-term care, policymakers often assume that larger, multi-state chains bring standardization: shared protocols, centralized oversight, and more consistent quality.  
This project examines whether that assumption holds.

Using publicly available CMS Nursing Home Chain Performance Measures, this analysis asks a structural question:

**Does consolidation standardize care — or does it standardize mediocrity while allowing risk to concentrate unevenly?**

---

## Data and Approach

The dataset aggregates performance at the **chain level**, covering thousands of nursing facilities across the United States.  
Each observation represents a nursing home chain, not an individual facility.

Rather than ranking chains or identifying “best” and “worst” performers, the analysis focuses on **variability** — how consistent outcomes are *within* chains of different sizes.

Why variability?  
Because systems rarely fail uniformly. They fail unevenly, quietly, and often in ways that averages conceal.

---

## Outcome Domains Examined

The analysis focuses on outcomes that reflect resident well-being and system performance, including:

- Functional decline among long-stay residents  
- Increased dependence in activities of daily living  
- Use of physical restraints  
- Weight loss and depression indicators  
- Potentially preventable hospital readmissions  

Chains were grouped by size (very small, small, medium, large), and outcomes were compared using the **coefficient of variation (CV)** — a measure of dispersion relative to the mean.

---

## Scale Does Not Guarantee Stability

In some areas, larger chains exhibit more predictable outcomes.

- Variability in system-level metrics such as hospital readmissions decreases with scale  
- Measures of functional decline also become more stable among larger organizations  

This suggests that consolidation can standardize certain operational processes, particularly around care transitions.

However, this apparent stability does not generalize across all dimensions of care.

---

## Harm-Related Outcomes Become More Uneven

For harm-related indicators — particularly physical restraint use and depression symptoms — variability **increases** with scale.

The largest chains exhibit the widest spread in these outcomes, indicating that:
- Some facilities perform well  
- Others deteriorate substantially  
- All operate under the same corporate umbrella  

In other words, consolidation does not eliminate risk.  
It redistributes it.

---

## Enforcement Signals Concentrate with Scale

CMS enforcement indicators reinforce this pattern.

Larger chains account for substantially higher numbers of:
- Special Focus Facilities (SFFs)  
- SFF candidates  

These designations reflect persistent quality concerns rather than isolated incidents.

Notably, the **percentage of facilities flagged with abuse indicators does not decline with size**.  
Scale increases oversight and visibility — not immunity.

---

## Ownership as a Modifier, Not a Verdict

Ownership structure further complicates the picture.

Across small and medium chains, for-profit–dominant ownership is associated with:
- Higher average rates of depression symptoms  
- Slightly higher readmission rates  
- Mixed patterns in functional decline  

However, these effects are not uniform across scale.  
At larger sizes, ownership-based averages converge — while **variability persists**.

This suggests that ownership alone does not determine outcomes.  
Instead, ownership interacts with scale, shaping where and how inconsistencies emerge.

The system’s behavior cannot be reduced to “for-profit versus non-profit.”  
The real fault line lies in how incentives, oversight, and operational complexity intersect.

---

## What This Reveals About Systemic Failure

This analysis does not identify villains.  
It identifies structures.

Large healthcare organizations do not fail loudly. They fail unevenly.

Some facilities stabilize. Others drift.  
Centralized policies coexist with localized degradation, and averages smooth over the cracks.

If quality truly scaled with size, variability would shrink across all domains.  
Instead, it migrates.

And that is where systems quietly fail.

---

## Why This Matters

As healthcare systems continue to consolidate — not only in nursing homes, but across hospitals, insurers, and treatment networks — understanding how failure distributes becomes as important as measuring performance itself.

When variability grows, outcomes depend less on policy and more on where — and under whom — a patient happens to receive care.

That is not a quality problem.  
It is a system design problem.

---

## Disclaimer

This project is an **independent structural analysis** using publicly available CMS data accessed via the CMS Open Data API.  
The findings are descriptive and exploratory, intended to examine system-level patterns rather than provide exhaustive enumeration, causal inference, or evaluation of individual facilities or organizations.

---

## Reproducibility

- Data source: CMS Nursing Home Chain Performance Measures  
- Unit of analysis: Nursing home chains  
- Methods: Outcome aggregation, scale stratification, coefficient of variation analysis  

The notebook included in this repository reproduces all results presented.
