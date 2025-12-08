# Scoring Matrix

This scoring matrix provides an example model for converting maturity assessments into a quantified,
comparable score across domains and capabilities.

NOTE: This scoring matrix is fictional and should be tailored to the business, regulatory
environment, and organizational context. It is provided to demonstrate how an organization might
derive scoring for its maturity model.

---

## 1. Scoring Scale

| Score | Meaning |
|-------|---------|
| 1 | Ad Hoc |
| 2 | Repeatable |
| 3 | Defined |
| 4 | Measured |
| 5 | Optimized |
| 0 | Optional: Not present or uncontrolled |

---

## 2. Example Weighting

Some capabilities may carry a higher weight due to risk or regulatory obligations.

| Capability | Weight |
|-----------|--------|
| IAM | 20% |
| Data Protection | 20% |
| Monitoring & Logging | 20% |
| Cloud Platform | 20% |
| Governance & Risk | 20% |

Weights should be adjusted for different industries or cloud footprints.

---

## 3. Scoring Formula (Example)

Single capability score formula:
Current Maturity ÷ Target Maturity

Domain score:
Weighted average of capability scores

Overall maturity score:
Average of all domain scores

---

## 4. Example Scoring Table

| Domain | Current | Target | Gap | Weighted Score |
|--------|---------|--------|-----|----------------|
| IAM | 2 | 4 | 2 | 0.50 |
| Data Protection | 3 | 4 | 1 | 0.75 |
| Monitoring | 2 | 4 | 2 | 0.50 |
| Cloud Platform | 1 | 4 | 3 | 0.25 |
| Governance & Risk | 3 | 4 | 1 | 0.75 |

Overall maturity example score:
(0.50 + 0.75 + 0.50 + 0.25 + 0.75) / 5 = 0.55 (55% maturity)

---

## 5. Customization Guidance

Organizations should adjust:

- Weights
- Risk factors
- Impact values
- Domain coverage
- Scoring method

based on:

- Business drivers
- Regulatory posture
- Risk tolerance
- Organizational complexity

This ensures the scoring matrix is meaningful rather than generic.
