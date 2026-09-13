# Third-Party & Vendor Risk Maturity Model

Third-Party & Vendor Risk maturity measures how effectively an organization identifies, evaluates, governs, monitors, and manages security and operational risk introduced by external organizations and services.

Third parties may include vendors, SaaS providers, cloud providers, contractors, service providers, business partners, data processors, technology suppliers, and other external entities that access organizational systems, data, infrastructure, or business processes.

This domain is closely connected to Governance & Risk, Identity & Access Management, Data Protection, Cloud Platform, Network Security, and business resilience.

---

## 1. Scope of the Third-Party & Vendor Risk Domain

Third-Party & Vendor Risk maturity includes:

* Vendor inventory and ownership
* Vendor classification and risk tiering
* Pre-contract due diligence
* Security assessments
* Contractual security requirements
* Data access and handling requirements
* Identity and access controls
* Third-party connectivity
* API and integration security
* Cloud and SaaS governance
* Shared-responsibility understanding
* SLA and service requirements
* Security incident notification requirements
* Ongoing vendor monitoring
* Periodic reassessment
* Evidence and assurance reviews
* Fourth-party and concentration-risk considerations
* Offboarding and access removal
* Data return, retention, and destruction requirements
* Risk acceptance and exception management

The domain covers security, technology, operational, contractual, and governance considerations associated with external dependencies.

---

## 2. Maturity Levels

### Level 1 – Ad Hoc

Third-party risk is managed inconsistently and primarily in response to individual business needs.

Typical characteristics include:

* No complete vendor inventory exists.
* Vendor onboarding varies by team or business unit.
* Security due diligence is inconsistent or absent.
* Contracts may lack defined security requirements.
* Third-party access is granted without consistent governance.
* Vendor data access is poorly understood.
* Offboarding processes are informal.
* Vendor risk may become visible primarily after incidents or audit findings.

### Level 2 – Repeatable

Basic third-party risk processes exist for selected vendors, but coverage and execution remain inconsistent.

Typical characteristics include:

* A vendor onboarding process exists.
* Critical or higher-profile vendors receive basic security assessments.
* Questionnaires or evidence reviews are used.
* Some contractual security requirements are established.
* Vendor approvals are documented but largely manual.
* Access requirements are reviewed for selected vendors.
* Periodic reassessment occurs inconsistently.
* Vendor ownership and risk acceptance responsibilities may not be clearly defined.

### Level 3 – Defined

A formal third-party risk lifecycle is established and applied across defined vendor populations.

Typical characteristics include:

* A centralized vendor inventory is maintained.
* Vendors are classified or tiered based on risk.
* Due diligence requirements are defined by vendor category or risk level.
* Contracts include appropriate security, privacy, and incident-notification requirements.
* Vendor data access and system connectivity are documented.
* Identity and access requirements are defined.
* Shared-responsibility expectations are documented for cloud and SaaS providers.
* Reassessment schedules are established.
* Offboarding includes access removal and data-handling requirements.
* Risk acceptance and exception processes are defined.

### Level 4 – Measured

Third-party controls are consistently applied and program effectiveness is measured.

Typical characteristics include:

* Vendor risk tiering drives assessment depth and review frequency.
* Assessment completion and outstanding findings are tracked.
* High-risk vendor remediation is monitored.
* Contractual security obligations are tracked.
* Vendor access is periodically reviewed.
* SLA and service-performance issues are monitored where relevant.
* Assurance evidence is collected and reviewed on defined cycles.
* Material vendor incidents are incorporated into risk reporting.
* Vendor concentration and critical-service dependencies are evaluated.
* Program metrics provide visibility into third-party risk.

Automated monitoring may supplement periodic assessments where it provides reliable and relevant information.

### Level 5 – Optimized

Third-party risk management continuously adapts to changes in vendor relationships, business dependencies, technology, and risk.

Typical characteristics include:

* Material changes in vendor risk can trigger reassessment.
* Vendor security telemetry or external risk information is incorporated where useful and reliable.
* Identity and access governance is integrated with vendor lifecycle processes.
* Third-party access can be automatically removed or restricted when defined lifecycle events occur.
* Data flows and integration dependencies are maintained for critical relationships.
* Critical vendor dependencies are incorporated into resilience planning.
* Concentration and fourth-party risk receive increased visibility where relevant.
* Risk-based controls are adjusted as vendor relationships change.
* Vendor incidents and assurance findings influence architecture and sourcing decisions.
* Third-party risk metrics inform enterprise risk and investment decisions.

Level 5 does not imply that every vendor must be continuously monitored or subject to the same controls. Mature third-party risk management applies oversight proportionate to the risk and business dependency presented by each relationship.

---

## 3. Capabilities to Score

Evaluate each capability using the **1–5 maturity scale**.

| Capability              | Assessment Focus                                                             |
| ----------------------- | ---------------------------------------------------------------------------- |
| Vendor Inventory        | Completeness, ownership, classification, and lifecycle status                |
| Risk Tiering            | Segmentation based on criticality, access, data, and business dependency     |
| Due Diligence           | Assessment depth, evidence, and review requirements                          |
| Contract Requirements   | Security, privacy, incident, audit, SLA, and termination provisions          |
| Shared Responsibility   | Understanding of provider versus organizational responsibilities             |
| Identity & Access       | Least privilege, authentication, lifecycle, review, and offboarding          |
| Data Protection         | Data access, encryption, retention, handling, and destruction                |
| Integration Controls    | API, SaaS, network, and other third-party connectivity                       |
| Ongoing Monitoring      | Reassessment, material changes, findings, and posture awareness              |
| Assurance Evidence      | SOC reports, certifications, testing evidence, and other assurance artifacts |
| Incident Management     | Notification, escalation, coordination, and contractual obligations          |
| Resilience & Dependency | Critical services, concentration risk, substitutability, and continuity      |
| Offboarding             | Access removal, integration removal, data return, retention, and destruction |
| Risk Acceptance         | Ownership, justification, approval, expiration, and tracking                 |

Capability scores should reflect operating effectiveness rather than the existence of a vendor-management process alone.

For example, collecting a SOC 2 report does not necessarily indicate mature due diligence if findings, scope limitations, complementary controls, or exceptions are not evaluated in the context of the organization's actual use of the vendor.

---

## 4. Business Impact of Third-Party & Vendor Risk Maturity

Higher maturity can support:

* Better visibility into external dependencies
* Reduced exposure from third-party access
* More informed sourcing decisions
* Stronger protection of sensitive data
* Improved supply-chain and service resilience
* More consistent cloud and SaaS adoption
* Improved regulatory and contractual compliance
* Faster response to vendor security incidents
* Better understanding of concentration risk
* More effective vendor remediation and accountability

Lower maturity may contribute to:

* Unknown vendor access
* Sensitive-data exposure
* Weak contractual protections
* Unmanaged external integrations
* Delayed notification of vendor incidents
* Service disruption from critical dependencies
* Incomplete offboarding
* Excessive third-party privileges
* Regulatory or contractual findings
* Poor understanding of shared security responsibilities
* Concentration risk involving critical providers

Third-party risk cannot be eliminated. The objective is to understand the dependency and maintain controls appropriate to the risk the relationship introduces.

---

## 5. Drivers of Target Maturity

Target maturity should reflect the organization's third-party dependency and risk rather than assuming every vendor requires the same level of oversight.

Relevant drivers include:

* Vendor criticality
* Type and sensitivity of accessible data
* Privileged or administrative access
* Network or system connectivity
* Business-process dependency
* Availability requirements
* Regulatory and contractual obligations
* Cloud and SaaS reliance
* Geographic and data-residency requirements
* Vendor concentration
* Substitutability of the provider
* Fourth-party dependencies
* Incident history
* Risk tolerance

Different vendor populations may justify different assessment depth and control requirements.

For example, a provider processing regulated customer information or supporting a critical business service may require more extensive due diligence, access controls, contractual protections, monitoring, and resilience planning than a vendor with no system access and minimal business impact.

Target maturity should therefore reflect the organization's overall ability to manage its third-party ecosystem. Individual vendor controls should be proportionate to the risk presented by each relationship.

---

## 6. Evidence and Assessment Inputs

Third-Party & Vendor Risk maturity should be supported by observable evidence.

Potential assessment inputs include:

* Vendor inventory
* Vendor ownership records
* Risk classification and tiering criteria
* Due diligence questionnaires
* Security assessment results
* SOC reports
* ISO certifications
* Penetration-test summaries where available and appropriate
* Cloud provider assurance documentation
* Shared-responsibility models
* Contracts and security addenda
* SLA and SLO terms
* Privacy and data-processing agreements
* Vendor data-flow diagrams
* Third-party integration diagrams
* API and connectivity documentation
* Identity and access records
* Access review results
* Vendor remediation plans
* Risk acceptance records
* Incident-notification records
* Periodic reassessment evidence
* Business continuity and resilience information
* Offboarding records
* Data deletion or return evidence

Assurance artifacts should be evaluated in context rather than treated as proof that a vendor presents acceptable risk.

---

## 7. Inputs to Gap Analysis

Once current and target maturity are established:

**Gap = Target Maturity - Current Maturity**

The maturity gap identifies where third-party risk capability requires improvement but does not determine remediation priority by itself.

Gap analysis should also consider:

* Vendor criticality
* Data sensitivity
* Privileged access
* Connectivity
* Business dependency
* Regulatory exposure
* Concentration risk
* Existing compensating controls
* Known findings
* Incident history
* Dependencies
* Cost and implementation effort
* Expected risk reduction

For example, a one-level maturity gap involving access governance for a critical cloud provider may warrant action before a larger process gap affecting low-risk vendors.

These findings become inputs to risk ranking and roadmap development.

---

## 8. Relationship to the Enterprise Maturity Framework

Third-Party & Vendor Risk is one domain within the broader Enterprise Security Maturity Framework.

Its maturity depends on and influences other domains, including:

* Governance & Risk
* Identity & Access Management
* Data Protection
* Cloud Platform
* Monitoring & Logging
* Network Security
* DevSecOps & CI/CD

Cross-domain dependencies should be considered during prioritization.

For example:

* IAM governs third-party identities and access lifecycle.
* Data Protection determines requirements for information shared with external parties.
* Cloud Platform establishes shared-responsibility and SaaS/cloud governance expectations.
* Network Security controls external connectivity and third-party communication paths.
* Monitoring & Logging provides visibility into third-party activity.
* DevSecOps & CI/CD introduces software supply-chain and external dependency considerations.
* Governance & Risk defines risk acceptance, ownership, contractual requirements, and oversight.

The objective is not simply to increase the Third-Party & Vendor Risk maturity score.

The objective is to understand external dependencies, apply controls proportionate to their risk, maintain accountability throughout the relationship lifecycle, and prevent third-party relationships from introducing unmanaged business or security risk.
