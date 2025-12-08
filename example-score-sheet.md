# Example Scoring Sheet (Filled-In)

This is a fictional example of a completed scoring sheet for an organization. It demonstrates how
current maturity, target maturity, gap, and weighted scoring might be represented for assessment.

NOTE: These values are hypothetical and serve as an illustration only.

---

## 1. Summary Table

| Domain | Current | Target | Gap | Weighted Score |
|--------|---------|--------|-----|----------------|
| IAM | 2 | 4 | 2 | 0.50 |
| Data Protection | 3 | 4 | 1 | 0.75 |
| Monitoring & Logging | 2 | 4 | 2 | 0.50 |
| Cloud Platform | 1 | 4 | 3 | 0.25 |
| Governance & Risk | 3 | 4 | 1 | 0.75 |

---

## 2. Overall Maturity Score

Overall maturity score:
(0.50 + 0.75 + 0.50 + 0.25 + 0.75) / 5 = 0.55 (55%)

---

## 3. Domain-Level Detail

### IAM
- Current maturity: 2 (Repeatable)
- Target maturity: 4 (Measured)
- Key gaps:
  - MFA not deployed organization-wide
  - Limited identity governance
  - Manual provisioning and reviews

### Data Protection
- Current maturity: 3 (Defined)
- Target maturity: 4 (Measured)
- Key gaps:
  - Inconsistent key rotation
  - Partial secrets management

### Monitoring & Logging
- Current maturity: 2 (Repeatable)
- Target maturity: 4 (Measured)
- Key gaps:
  - Limited SIEM coverage
  - Incident playbooks are informal
  - Limited alert correlation

### Cloud Platform
- Current maturity: 1 (Ad Hoc)
- Target maturity: 4 (Measured)
- Key gaps:
  - No landing zone
  - No IaC patterns or guardrails
  - No centralized governance

### Governance & Risk
- Current maturity: 3 (Defined)
- Target maturity: 4 (Measured)
- Key gaps:
  - Inconsistent policy lifecycle enforcement
  - Manual risk reporting

---

## 4. Strategic Takeaways

- Cloud Platform and IAM have the largest gaps.
- Improving Cloud Platform has compound benefits across all other domains.
- Governance maturity is trending positively but needs operationalization.
- Monitoring maturity is required for incident response, compliance, and Zero Trust.

---

## 5. Next Steps

- Validate scores with stakeholders
- Use the gap analysis to develop roadmap initiatives
- Align maturity objectives with business priorities
