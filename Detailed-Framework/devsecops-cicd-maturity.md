# DevSecOps & CI/CD Maturity Model

DevSecOps & CI/CD maturity measures how effectively an organization integrates security, quality, governance, and repeatability into the software delivery lifecycle.

This domain evaluates not only whether CI/CD automation exists, but whether software changes can move from development through production using defined security controls, trusted artifacts, controlled identities, measurable gates, and auditable release processes.

---

## 1. Scope of the DevSecOps & CI/CD Domain

DevSecOps & CI/CD maturity includes:

* CI/CD pipeline automation and repeatability
* Secure SDLC integration
* Source code and branch protections
* Code review and change controls
* Static Application Security Testing (SAST)
* Software Composition Analysis (SCA)
* Dynamic Application Security Testing (DAST)
* Secrets scanning
* Infrastructure as Code (IaC) scanning
* Container and image scanning
* Software Bill of Materials (SBOM)
* Artifact integrity and repository controls
* Pipeline secrets management
* Pipeline and workload identities
* Security and quality gates
* Exception handling
* Release governance
* Environment separation
* Deployment and rollback strategies
* Pipeline logging, metrics, and auditability
* Threat modeling integration

The domain covers both the technical pipeline and the governance processes surrounding software delivery.

---

## 2. Maturity Levels

### Level 1 – Ad Hoc

Software delivery processes are largely manual and vary significantly across teams.

Typical characteristics include:

* Builds and deployments are performed manually.
* Scripts and automation are inconsistent or dependent on individual knowledge.
* No standard CI/CD pipeline pattern exists.
* Security testing is limited or performed late in the delivery process.
* Credentials may be embedded in scripts or configuration.
* Release processes are inconsistently documented.
* Production changes may depend heavily on manual intervention.

### Level 2 – Repeatable

Basic CI/CD and security practices exist for selected teams or applications, but adoption is inconsistent.

Typical characteristics include:

* Some applications use automated pipelines.
* Common CI/CD platforms are established for portions of the environment.
* Basic unit testing is integrated.
* Security scanning may be manual or optional.
* Basic branch and code review practices exist.
* Some pipeline secrets are moved into managed stores.
* Release and rollback procedures exist for selected workloads.
* Pipeline security depends heavily on individual team implementation.

### Level 3 – Defined

Standard software delivery and security patterns are established across defined application groups.

Typical characteristics include:

* Standardized CI/CD pipeline patterns are used across multiple applications.
* SAST and SCA are integrated into delivery workflows.
* Secrets scanning is incorporated into defined pipeline stages.
* Pipeline credentials and secrets are managed through approved mechanisms.
* Infrastructure as Code is commonly used for infrastructure deployments.
* IaC security scanning is incorporated where applicable.
* Promotion workflows between environments are defined.
* Artifact repositories and release processes are standardized.
* Security findings have defined ownership and remediation processes.
* Exceptions to security requirements are documented and approved.
* Threat modeling is incorporated for applications or changes where risk warrants it.

### Level 4 – Measured

Pipeline controls are consistently enforced and their effectiveness is measured.

Typical characteristics include:

* SAST, SCA, secrets scanning, IaC scanning, and other applicable security tests are consistently integrated.
* DAST is incorporated for appropriate applications and environments.
* Container and image scanning is integrated where containers are used.
* Security and quality gates enforce defined thresholds.
* Pipeline exceptions are time-bound, approved, and auditable.
* Artifact integrity and provenance controls are established.
* SBOM generation is incorporated where required.
* Deployment approvals and environment separation are enforced based on risk.
* Rollback or recovery procedures are tested.
* CI/CD metrics, audit logs, and security reporting are available.
* Least privilege is applied to pipeline identities and build systems.
* Persistent credentials are reduced where short-lived or federated identities can be used.
* Security findings and gate failures are measured to identify recurring problems.

### Level 5 – Optimized

Software delivery operates as a mature, continuously improving capability with security integrated into reusable platform patterns.

Typical characteristics include:

* Secure delivery patterns are provided through reusable or self-service pipelines.
* Policy-as-code is used where appropriate to enforce defined security requirements.
* Security baselines are incorporated into approved pipeline templates.
* Trusted artifact and software supply-chain controls are broadly implemented.
* Pipeline and workload identities use strong, short-lived authentication patterns where supported.
* Automated remediation is used for well-understood and low-risk conditions.
* Threat modeling is integrated into architecture and delivery workflows based on application and change risk.
* Compliance evidence can be generated from pipeline activity and control results.
* Security telemetry from development and production informs future pipeline controls.
* Deployment strategies support controlled releases and recovery.
* Pipeline performance and security outcomes are continuously evaluated and improved.

Level 5 does not imply that every security decision or deployment is fully automated. Human review remains appropriate for architectural decisions, significant risk acceptance, sensitive releases, and exceptions requiring judgment.

---

## 3. Capabilities to Score

Evaluate each capability using the **1–5 maturity scale**.

| Capability                | Assessment Focus                                                        |
| ------------------------- | ----------------------------------------------------------------------- |
| Pipeline Automation       | Repeatability of build, test, promotion, and deployment processes       |
| Source Control Governance | Branch protections, reviews, approvals, and change traceability         |
| SAST                      | Static analysis coverage, enforcement, and remediation                  |
| SCA                       | Dependency vulnerability and license-risk management                    |
| Secrets Scanning          | Detection and prevention of exposed credentials and secrets             |
| IaC Security              | Security validation of infrastructure definitions before deployment     |
| DAST                      | Runtime application security testing where appropriate                  |
| Container Security        | Image scanning, trusted images, and container artifact controls         |
| Artifact Management       | Repository controls, integrity, provenance, and promotion               |
| SBOM                      | Software component visibility and supply-chain evidence                 |
| Secrets Management        | Secure pipeline secret storage, access, rotation, and lifecycle         |
| Pipeline Identity         | Least privilege, machine identity, federation, and credential lifecycle |
| Security Gates            | Defined pass/fail criteria and enforcement                              |
| Exception Management      | Approval, justification, expiration, and auditability                   |
| Release Governance        | Promotion, approvals, deployment controls, and rollback                 |
| Testing Coverage          | Unit, integration, security, and other applicable testing               |
| Metrics & Auditing        | Pipeline logs, findings, dashboards, and change traceability            |
| Policy-as-Code            | Automated enforcement of defined policies where appropriate             |
| Threat Modeling           | Risk-based integration of design and architecture security analysis     |

Capability scores should reflect both control implementation and operating effectiveness.

For example, installing a SAST tool does not indicate mature SAST capability if scans are optional, findings are ignored, thresholds are undefined, or developers can bypass the control without an approved exception.

---

## 4. Business Impact of DevSecOps & CI/CD Maturity

Higher maturity can support:

* Faster and more predictable software delivery
* Earlier identification of security defects
* Reduced cost of remediation
* Consistent deployment practices
* Reduced configuration and release risk
* Improved software supply-chain security
* Stronger auditability
* Improved developer and security collaboration
* Faster recovery from failed releases
* Greater confidence in production changes
* Regulatory and contractual evidence

Lower maturity may contribute to:

* Vulnerabilities reaching production
* Exposed secrets
* Inconsistent environments
* Unauthorized or poorly controlled changes
* Untrusted artifacts
* Production outages
* Manual release failures
* Weak audit trails
* Delayed remediation
* Excessive pipeline permissions
* Security controls being bypassed under delivery pressure

The business impact depends on application criticality, deployment frequency, data sensitivity, exposure, and the consequences of a failed or compromised release.

---

## 5. Drivers of Target Maturity

Target maturity should reflect the organization's software delivery risk and business requirements rather than assuming every application requires the same pipeline controls.

Relevant drivers include:

* Application criticality
* Data sensitivity
* Internet exposure
* Deployment frequency
* Development model
* Regulatory and contractual requirements
* Software supply-chain risk
* Cloud adoption
* Container and IaC usage
* Number of development teams
* Application portfolio complexity
* Availability requirements
* Recovery requirements
* Risk tolerance
* Internal engineering capacity

Different applications may justify different control depth.

For example, an internet-facing payment application may require stronger security gates, artifact controls, identity protections, and release governance than a low-risk internal utility.

Target maturity should therefore be driven by business and application risk rather than by the desire to maximize the maturity score.

---

## 6. Evidence and Assessment Inputs

DevSecOps & CI/CD maturity should be supported by observable evidence.

Potential assessment inputs include:

* CI/CD pipeline configurations
* Source control settings
* Branch protection rules
* Pull request and approval workflows
* SAST reports
* SCA reports
* Secrets scanning results
* IaC scanning results
* DAST results
* Container and image scanning results
* SBOM artifacts
* Artifact repository configurations
* Artifact signing or provenance evidence
* Pipeline service-account and machine-identity configurations
* Secrets management configurations
* Security gate definitions
* Exception records
* Deployment approval workflows
* Release history
* Rollback procedures and test results
* Pipeline audit logs
* Security dashboards
* Incident records related to software delivery
* Threat models and architecture reviews

Evidence should demonstrate how controls operate in practice rather than simply confirming that a tool has been purchased or a policy exists.

---

## 7. Inputs to Gap Analysis

Once current and target maturity are established:

**Gap = Target Maturity - Current Maturity**

The maturity gap identifies where additional capability is required but does not determine remediation priority by itself.

Gap analysis should also consider:

* Application criticality
* Security risk
* Internet exposure
* Data sensitivity
* Regulatory or contractual urgency
* Frequency of software changes
* Existing compensating controls
* Dependencies
* Cost and implementation effort
* Expected risk reduction

For example, a one-level gap in pipeline identity affecting privileged production deployments may deserve higher priority than a larger maturity gap affecting a low-risk internal application.

These findings become inputs to risk ranking and roadmap development.

---

## 8. Relationship to the Enterprise Maturity Framework

DevSecOps & CI/CD is one domain within the broader Enterprise Security Maturity Framework.

Its maturity depends on and influences other domains, including:

* Governance & Risk
* Identity & Access Management
* Data Protection
* Cloud Platform
* Monitoring & Logging
* Network Security
* Third-Party / Vendor Risk

Cross-domain dependencies should be considered during prioritization.

For example:

* Pipeline identities depend on mature IAM practices.
* IaC guardrails depend on Cloud Platform governance.
* Security telemetry depends on Monitoring & Logging.
* Application secrets and sensitive data handling depend on Data Protection.
* Third-party dependencies and software components introduce Vendor and supply-chain risk.
* Exception handling and risk acceptance depend on Governance & Risk.

The objective is not simply to increase the DevSecOps maturity score. It is to improve the organization's ability to deliver software securely, consistently, and at a level of control appropriate to the business risk.
