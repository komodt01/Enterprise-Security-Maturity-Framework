# Scoring Matrix

This scoring matrix provides an example model for converting maturity assessments into quantified, comparable results across security domains and capabilities.

**NOTE:** This scoring matrix is fictional and should be tailored to the business, regulatory environment, risk profile, and organizational context. It demonstrates one way an organization might measure progress toward target maturity while keeping maturity measurement separate from risk-based prioritization.

---

## 1. Scoring Scale

| Score | Meaning                               |
| ----: | ------------------------------------- |
|     0 | Optional: Not present or uncontrolled |
|     1 | Ad Hoc                                |
|     2 | Repeatable                            |
|     3 | Defined                               |
|     4 | Measured                              |
|     5 | Optimized                             |

Current and target maturity levels are assigned based on assessment evidence, stakeholder input, and the organization's desired security posture.

---

## 2. Example Weighting

Some domains or capabilities may carry greater importance because of business criticality, risk exposure, regulatory obligations, or organizational priorities.

For simplicity, this example uses equal weighting:

| Domain               | Weight |
| -------------------- | -----: |
| IAM                  |    20% |
| Data Protection      |    20% |
| Monitoring & Logging |    20% |
| Cloud Platform       |    20% |
| Governance & Risk    |    20% |

Equal weighting is used only for illustration. In an actual assessment, weights may differ based on the organization's business model, regulatory requirements, technology environment, risk tolerance, and transformation objectives.

---

## 3. Maturity Attainment

Maturity attainment measures progress from the current state toward the defined target state.

**Maturity Attainment = Current Maturity ÷ Target Maturity**

For example:

* Current maturity = 2
* Target maturity = 4
* Maturity attainment = 2 ÷ 4 = 0.50, or 50%

This measurement answers:

**How close is the capability or domain to its defined target maturity?**

Domain maturity attainment may be calculated from the capability scores within that domain.

Overall target attainment may then be calculated from the domain maturity attainment scores.

Maturity attainment is not a risk score and does not, by itself, determine remediation priority.

---

## 4. Example Scoring Table

| Domain               | Current | Target | Gap | Maturity Attainment |
| -------------------- | ------: | -----: | --: | ------------------: |
| IAM                  |       2 |      4 |   2 |                0.50 |
| Data Protection      |       3 |      4 |   1 |                0.75 |
| Monitoring & Logging |       2 |      4 |   2 |                0.50 |
| Cloud Platform       |       1 |      4 |   3 |                0.25 |
| Governance & Risk    |       3 |      4 |   1 |                0.75 |

**Overall Target Attainment:**

(0.50 + 0.75 + 0.50 + 0.25 + 0.75) / 5 = **0.55 (55%)**

In this fictional example, the organization has achieved approximately 55% of the maturity represented by its defined target levels.

This does not mean the organization is "55% secure." It represents progress toward the target maturity defined for the assessed domains.

---

## 5. Gap Measurement

The maturity gap represents the difference between the current and target maturity levels.

**Gap = Target Maturity - Current Maturity**

For example:

* Current maturity = 1
* Target maturity = 4
* Gap = 3

A larger maturity gap identifies a greater difference between current and desired capability maturity.

However, gap size alone should not determine remediation priority.

A smaller gap affecting a highly critical business capability may require action before a larger gap with lower business or security impact.

---

## 6. Risk-Based Prioritization

Maturity measurement identifies where capability gaps exist. Risk-based prioritization determines which gaps should be addressed first.

Prioritization may consider:

* Maturity gap
* Risk severity
* Business criticality
* Regulatory or audit urgency
* Dependencies
* Cost and effort of remediation
* Expected risk reduction

A conceptual prioritization model may be represented as:

**Priority Score = Gap × Risk × Weighting Factors**

The specific weighting factors and scoring ranges should be defined by the organization rather than treated as universal values.

The resulting priority score should support architectural judgment, not replace it.

For example, a domain with a lower maturity level does not automatically receive the highest remediation priority. A smaller IAM gap affecting privileged access could present greater immediate risk than a larger maturity gap in a less critical capability.

---

## 7. Using the Results

The assessment results support two related but different decisions:

**Maturity Attainment**

Shows how close the organization is to its defined target state.

**Risk-Based Prioritization**

Shows where remediation effort and investment should be directed first.

Together, these provide inputs for:

* Gap analysis
* Risk ranking
* Roadmap development
* Investment prioritization
* Architecture planning
* Security transformation initiatives
* Future reassessment

---

## 8. Customization Guidance

Organizations should adjust the model based on their own environment.

Areas that may require customization include:

* Domain and capability coverage
* Current and target maturity criteria
* Domain or capability weights
* Risk factors
* Business impact values
* Regulatory considerations
* Prioritization methodology
* Scoring thresholds

These decisions should reflect:

* Business drivers
* Regulatory posture
* Risk tolerance
* Organizational complexity
* Technology and cloud footprint
* Critical business services
* Transformation objectives

The scoring model is intended to support structured decision-making. It should not replace risk analysis, stakeholder judgment, or architecture review.
