# Cloud Platform Maturity Model

Cloud Platform maturity measures how effectively an organization designs, governs, deploys, and operates cloud workloads with repeatability, security, resilience, and consistency.

This domain focuses on architectural readiness, governance, operationalization, and the ability to scale cloud adoption without creating unmanaged security or operational risk.

---

## 1. Scope of the Cloud Platform Domain

Cloud Platform maturity includes:

* Landing zone and account/subscription architecture
* Network segmentation and secure connectivity
* Identity boundaries across cloud resources
* Standardized provisioning and configuration patterns
* Infrastructure as Code (IaC) adoption
* Guardrails and policy enforcement
* Cloud governance and operating models
* Workload and tenant onboarding
* Cloud-native service baselines
* Observability and operational readiness
* Resilience and recovery considerations

The domain encompasses both platform engineering capabilities and the governance mechanisms used to maintain a secure and consistent cloud environment.

---

## 2. Maturity Levels

### Level 1 – Ad Hoc

Cloud adoption is largely decentralized and inconsistent.

Typical characteristics include:

* Cloud usage is unstructured.
* Workloads are commonly deployed manually.
* No consistent multi-account or subscription strategy exists.
* Network architecture varies by workload or team.
* Security controls depend heavily on individual implementation decisions.
* Guardrails are weak or nonexistent.
* Logging, backup, and identity practices are inconsistent.

### Level 2 – Repeatable

Common practices begin to emerge, but implementation remains inconsistent across the environment.

Typical characteristics include:

* Basic cloud governance practices exist.
* Standard configurations are used for some workloads.
* Account or subscription segmentation is partially implemented.
* Basic backup, logging, and IAM practices are established.
* Some reusable provisioning patterns exist.
* Network and security standards are documented for selected environments.
* Workload onboarding still requires significant manual coordination.

### Level 3 – Defined

The organization has established repeatable cloud architecture and governance patterns.

Typical characteristics include:

* A landing zone or organizational cloud baseline is established.
* Multi-account or subscription architecture is defined.
* Standard patterns exist for networking, IAM, logging, and monitoring.
* Infrastructure provisioning is largely standardized through IaC.
* Workload onboarding processes are documented and repeatable.
* Cloud governance responsibilities are defined.
* Security and operational requirements are incorporated into platform standards.

### Level 4 – Measured

Cloud platform controls are consistently implemented and their effectiveness is measured.

Typical characteristics include:

* Mandatory guardrails and policies are enforced through automation where appropriate.
* IaC adoption is consistent across teams and environments.
* Network, IAM, logging, and security baselines are automated.
* Cloud resource compliance is measured and reported.
* Exceptions and policy deviations are tracked.
* Workload onboarding and platform adoption are measured.
* Operational and security metrics are used to identify gaps and improve platform performance.

### Level 5 – Optimized

The cloud platform operates as a mature shared capability that continuously adapts to business, security, and operational requirements.

Typical characteristics include:

* The cloud platform is codified and managed as a product or shared service.
* Multi-account or subscription architecture scales with organizational needs.
* Continuous compliance and policy-as-code are broadly implemented.
* Risk-based controls can be applied dynamically where appropriate.
* Automated remediation is used for well-understood conditions.
* Self-service workload onboarding incorporates required guardrails.
* Resilience, recovery, observability, and cost controls are integrated into platform patterns.
* Metrics and operational experience continuously influence platform improvement.

---

## 3. Capabilities to Score

Each capability can be evaluated using the **1–5 maturity scale**.

| Capability             | Assessment Focus                                                       |
| ---------------------- | ---------------------------------------------------------------------- |
| Landing Zone           | Multi-account/subscription architecture and baseline services          |
| IaC Adoption           | Standardized, repeatable infrastructure provisioning                   |
| Policy & Guardrails    | Preventive and detective configuration controls                        |
| Networking             | Segmentation, routing, connectivity, and network security patterns     |
| Identity Boundaries    | IAM, federation, privileged access, and workload access                |
| Observability Baseline | Logging, audit, monitoring, and metrics                                |
| Workload Onboarding    | Repeatability, security requirements, and governance                   |
| Platform Operations    | Monitoring, resilience, recovery, hardening, and operational ownership |

Capability scores should be based on evidence rather than the existence of a policy or technology alone.

For example, the presence of an IaC repository does not necessarily indicate mature IaC adoption if teams continue to deploy significant infrastructure manually.

---

## 4. Business Impact of Cloud Platform Maturity

A mature cloud platform can enable:

* Repeatable and secure workload deployment
* Reduced configuration drift
* Lower operational and security risk
* Faster workload onboarding
* Greater delivery consistency
* Improved governance and compliance
* Better visibility across cloud environments
* Improved availability and resilience
* More predictable operational cost
* Standardization across teams and cloud providers

Lower maturity may contribute to:

* Configuration drift
* Cloud misconfigurations
* Inconsistent security controls
* Excessive permissions
* Limited visibility
* Unmanaged or unpredictable cost
* Slow workload onboarding
* Compliance gaps
* Operational outages
* Increased dependence on manual processes

The business impact of a maturity gap depends on the workloads and services affected. The same technical gap may present very different risk depending on business criticality, data sensitivity, regulatory requirements, and exposure.

---

## 5. Drivers of Target Maturity

Target maturity should be determined by organizational requirements rather than assuming every capability must reach Level 5.

Relevant drivers include:

* Cloud adoption strategy
* Organizational size and cloud footprint
* Business criticality of cloud-hosted services
* Data sensitivity
* Regulatory and compliance obligations
* Risk tolerance
* Speed-to-market objectives
* Digital transformation goals
* SLA and SLO requirements
* Operational complexity
* Multi-cloud or hybrid-cloud requirements
* Available operating capacity and investment

For example, a regulated organization operating critical customer-facing services may require highly measured and automated controls in identity, logging, resilience, and policy enforcement while accepting a different maturity target for a lower-risk capability.

Target maturity therefore represents the level required to support the organization's business and risk objectives, not simply the highest achievable score.

---

## 6. Evidence and Assessment Inputs

Cloud Platform maturity should be supported by observable evidence.

Potential assessment inputs include:

* Cloud landing zone documentation and architecture
* Account, subscription, or project hierarchy
* IaC repositories
* CI/CD pipeline usage
* Cloud Security Posture Management (CSPM) reporting
* Cloud compliance reporting
* Policy and guardrail configurations
* Network architecture and segmentation patterns
* IAM and federation architecture
* Privileged access controls
* Logging and monitoring architecture
* Backup and recovery configurations
* Resilience and disaster recovery documentation
* Workload onboarding procedures
* Exception records
* Audit findings
* Incident reports
* Platform metrics and operational reporting

The evidence examined should reflect the capability being scored. Assessment conclusions should not rely solely on interviews or documented policy when technical or operational evidence is available.

---

## 7. Inputs to Gap Analysis

Once current and target maturity have been established, the assessment identifies the difference between the two states.

**Gap = Target Maturity - Current Maturity**

The gap identifies where improvement is required but does not determine remediation priority by itself.

Gap analysis should also consider:

* Business impact
* Risk severity
* Regulatory or audit urgency
* Critical dependencies
* Existing compensating controls
* Cost and implementation effort
* Expected risk reduction

For example, a large gap in one cloud capability may be less urgent than a smaller identity or logging gap affecting a critical regulated workload.

These findings become inputs to risk ranking and roadmap development.

---

## 8. Relationship to the Enterprise Maturity Framework

Cloud Platform is one domain within the broader Enterprise Security Maturity Framework.

Its results should be evaluated alongside other domains such as:

* Governance & Risk
* Identity & Access Management
* Data Protection
* Monitoring & Logging
* Network Security
* DevSecOps & CI/CD
* Third-Party / Vendor Risk

Dependencies between domains should be considered during prioritization.

For example, improving cloud platform automation may depend on mature identity, logging, or governance capabilities. Likewise, standardized cloud platform controls may improve maturity across several other domains.

The purpose of the assessment is therefore not simply to increase individual maturity scores. It is to identify the combination of improvements that most effectively reduces risk and supports the organization's business objectives.
