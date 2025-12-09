# Cloud Platform Maturity Model

Cloud Platform maturity measures how effectively an organization designs, governs, deploys, and
operates workloads in the cloud with repeatability, security, and consistency. This domain focuses
on architectural readiness, operationalization, and secure cloud footprint design.

---

## 1. Scope of the Cloud Platform Domain

Cloud Platform maturity includes:

- Landing zone and account/subscription architecture
- Network segmentation and secure connectivity
- Identity boundaries across cloud resources
- Standardized provisioning and configuration patterns
- Infrastructure as Code (IaC) consistency
- Guardrails and policy enforcement
- Cloud governance and operational models
- Onboarding of workloads and tenants
- Cloud-native service baselines

It encompasses both platform engineering and cloud governance.

---

## 2. Maturity Levels

### Level 1 – Ad Hoc
- Cloud usage is unstructured.
- Workloads deployed manually (click-ops).
- No multi-account/subscription strategy.
- Weak or nonexistent guardrails and network design.

### Level 2 – Repeatable
- Some governance begins to emerge.
- Standard cloud configurations for select workloads.
- Partial account/subscription segmentation.
- Basic backup, logging, and IAM practices.

### Level 3 – Defined
- Landing zone or organizational baseline established.
- Multi-account/subscription model defined and enforced.
- Standard patterns for networking, IAM, logging, and monitoring.
- Infrastructure provisioning largely standardized via IaC.
- Workload onboarding is known and documented.

### Level 4 – Measured
- Guardrails and mandatory policies enforced via automation.
- Consistent IaC adoption across teams.
- Network, IAM, and logging baselines automated.
- Cloud resource compliance measured and reported.
- Workload onboarding and platform adoption tracked and optimized.

### Level 5 – Optimized
- Cloud platform is **codified** as a product or shared service.
- Scalable multi-account/subscription architecture.
- Continuous compliance and policy-as-code.
- Risk-based controls automatically applied.
- Automated remediation and self-service workload onboarding.
- Cloud-native resilience and cost controls built in.

---

## 3. Capabilities to Score

Score each on a **1–5 maturity scale**:

| Capability | Notes |
|-----------|-------|
| Landing Zone | Multi-account/subscription baseline |
| IaC Adoption | Provisioning and repeatability |
| Policy & Guardrails | Mandatory config standards |
| Networking | Secure segmentation & routing |
| Identity Boundaries | IAM, federation, access control |
| Observability Baseline | Logging + audit + metrics |
| Workload Onboarding | Repeatability + governance |
| Platform Operations | Monitoring, DR, hardening |

---

## 4. Business Impact of Cloud Platform Maturity

A mature cloud platform enables:

- Repeatable, secure workload deployment
- Reduced operational cost and risk
- Faster cloud adoption and delivery velocity
- Built-in governance and compliance posture
- Improved availability and resilience
- Standardization across teams and cloud providers

Lower maturity increases the chance of:
- cloud drift
- misconfigurations
- unmanaged cost
- security breaches
- operational outages

---

## 5. Drivers of Target Maturity

Target maturity depends on:

- Cloud adoption strategy
- Organizational size and cloud footprint
- Regulatory or compliance landscape
- Speed-to-market and digital transformation goals
- Workload criticality and SLA/SLO requirements

Not all organizations need Level 5, but Level 3–4 is typical for enterprises.

---

## 6. Inputs to Gap Analysis

Artifacts that reveal maturity gaps include:

- Cloud landing zone documentation and architecture
- IaC repositories and pipeline usage
- CSPM/CA/Compliance reporting
- Network and IAM standard patterns
- Monitoring & logging architecture
- Cloud governance committee structures
- Audit and incident reports

These inputs guide roadmap priorities for improving cloud platform maturity.
