# Monitoring & Logging Maturity Model

Monitoring and logging maturity measures how effectively an organization detects, observes, and
responds to events in systems, applications, and cloud environments. This is foundational for
incident response, visibility, compliance, and Zero Trust.

---

## 1. Scope of the Monitoring & Logging Domain

This domain includes:

- Cloud logging and audit visibility
- System and application logs
- SIEM and log aggregation
- Alerting and triage workflows
- Metrics, dashboards, and observability
- Incident response integration
- Continuous monitoring
- Security telemetry standards

Monitoring maturity evaluates both **technical telemetry** and **operational processes**.

---

## 2. Maturity Levels

### Level 1 – Ad Hoc
- Limited logging, mostly default or unmanaged.
- Logs are fragmented and reside in separate tools.
- Event monitoring is **reactive** or manual.
- No centralized alerting or response.
- Incidents identified only after impact.

### Level 2 – Repeatable
- Some centralized log storage or aggregation.
- Alerts exist but may be noisy or inconsistent.
- Basic monitoring for critical assets.
- Limited monitoring coverage of cloud workloads.

### Level 3 – Defined
- Logs from all critical workloads collected centrally.
- SIEM or monitoring platform deployed.
- Playbooks exist for alert review and triage.
- Basic threat detection and alert prioritization.
- Visibility into most cloud accounts and applications.

### Level 4 – Measured
- Dashboards, KPIs, and alert hygiene in place.
- Automated alert correlation and suppression.
- Incident response integration.
- Baselines and anomaly detection.
- Log coverage is quantified and monitored.

### Level 5 – Optimized
- Continuous telemetry and threat analytics.
- Automated investigation and containment workflows.
- Behavior analytics and threat intelligence feeds.
- Policy-as-code and governance controls for log collection.
- Real-time alerting tied to Zero Trust enforcement.

---

## 3. Capabilities to Score

Each capability is evaluated on a **1–5 maturity scale**:

| Capability | Notes |
|-----------|-------|
| Log Collection | Cloud + application + system logs |
| Centralization | SIEM/aggregation platform |
| Alerting | Prioritization, correlation |
| Monitoring Metrics | Coverage %, uptime, SLA/SLO |
| Incident Response | Playbooks + workflows |
| Threat Detection | Analytics, behavior models |
| Continuous Visibility | Cloud audit + identity events |
| Automation | SOAR, triage, remediation |

These create the assessment matrix for maturity scoring.

---

## 4. Business Impact of Monitoring Maturity

Higher maturity improves:

- Detection and containment speed
- Compliance posture (PCI, ISO, FFIEC, SOX)
- Root cause, auditability, and forensics
- Uptime and operational resilience
- Incident response and recovery time

Monitoring maturity reduces the likelihood and impact of breaches.

---

## 5. Drivers of Target Maturity

Target state is shaped by:

- Regulatory requirements
- SLAs, SLOs, and uptime guarantees
- Cloud scale and complexity
- Digital transformation and production workloads
- Cost and operational staffing

Not every organization needs Level 5 analytics and SOAR on day one.

---

## 6. Inputs to Gap Analysis

- Logging architecture diagrams
- SIEM or log aggregator coverage
- Incident response workflows
- Monitoring dashboards and metrics
- Alert tuning and noise reduction methods
- Cloud audit logs and IAM logs
- Data retention and searchability

These artifacts identify gaps in logging/monitoring maturity and guide roadmap priorities.
