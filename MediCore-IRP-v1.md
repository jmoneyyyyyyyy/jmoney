# MediCore Health Systems – Incident Response Plan

**Version:** 1.0
**Date:** June 2026
**Owner:** Lead Cloud Security Architect

---

# 1. Purpose

This Incident Response Plan (IRP) defines the process for identifying, responding to, containing, eradicating and recovering from cybersecurity incidents that may affect MediCore Health Systems, its services and patient data.

---

# 2. Roles and Responsibilities

| Role                                    | Responsibility                                         | Contact Method       | Response Time   |
| --------------------------------------- | ------------------------------------------------------ | -------------------- | --------------- |
| Incident Lead                           | Coordinates incident response activities               | Microsoft Teams      | 15 minutes      |
| Data Protection Officer (DPO)           | Assesses GDPR impact and breach reporting requirements | Direct Phone         | 2 hours         |
| Chief Technology Officer (CTO)          | Approves business and technical decisions              | Microsoft Teams      | 2 hours         |
| Information Commissioner's Office (ICO) | Receives GDPR breach notifications                     | ICO Reporting Portal | Within 72 hours |
| NHS Trusts                              | Receive service disruption notifications               | Secure Email         | 4 hours         |

---

# 3. Detection Triggers (Phase 2 – Identification)

| Alert                                            | Who is Notified       | SLA        | Phase   |
| ------------------------------------------------ | --------------------- | ---------- | ------- |
| CPU usage above 80% for more than 3 minutes      | Incident Lead         | 15 minutes | Phase 2 |
| Three or more failed SSH logins within 5 minutes | Incident Lead and CTO | 5 minutes  | Phase 2 |
| Database access from an unauthorised source      | DPO                   | Immediate  | Phase 2 |
| Patient data accessed outside approved hours     | DPO and CTO           | Immediate  | Phase 2 |
| Storage access from outside the virtual network  | Incident Lead         | 10 minutes | Phase 2 |

---

# 4. Containment Procedures (Phase 3)

## Unauthorised Access Incident

1. Preserve all logs and forensic evidence.
2. Isolate affected systems from the network.
3. Disable compromised user accounts and credentials.
4. Notify the CTO and DPO immediately.
5. Prevent further unauthorised access.
6. Record all actions taken during the incident.

---

# 5. Eradication Procedures (Phase 4)

1. Identify the root cause of the incident.
2. Remove malicious files, accounts or software.
3. Apply security patches and updates.
4. Rebuild affected systems from clean images if required.
5. Verify that security controls are functioning correctly.
6. Confirm that no malicious activity remains.

---

# 6. Recovery Procedures (Phase 5)

1. Restore systems and data from verified backups.
2. Test system functionality and integrity.
3. Resume business operations gradually.
4. Monitor systems for suspicious activity.
5. Continue enhanced monitoring for at least 72 hours.

---

# 7. Lessons Learned (Phase 6)

Following every incident:

1. Conduct a post-incident review.
2. Identify security improvements.
3. Update the risk register.
4. Update this Incident Response Plan where required.
5. Deliver additional staff awareness training if necessary.

---

# 8. GDPR Breach Notification Process (Article 33)

| Time           | Action                                                  |
| -------------- | ------------------------------------------------------- |
| T+0 Hours      | Breach identified and incident response process started |
| T+2 Hours      | CTO and DPO notified                                    |
| T+8 Hours      | DPO completes initial risk assessment                   |
| T+24 Hours     | Draft ICO notification prepared                         |
| T+72 Hours     | ICO notification submitted                              |
| After 72 Hours | Data subjects informed if high risk is identified       |

---

# 9. Incident Response Lifecycle

### Phase 1 – Preparation

Security controls, monitoring, policies and staff training are maintained.

### Phase 2 – Identification

Security alerts, monitoring systems or staff identify a potential incident.

### Phase 3 – Containment

Affected systems are isolated to prevent further damage.

### Phase 4 – Eradication

The cause of the incident is removed and vulnerabilities are addressed.

### Phase 5 – Recovery

Systems and services are restored safely.

### Phase 6 – Lessons Learned

The incident is reviewed and improvements are implemented.

---

# Screenshot Evidence

## Screenshot 23 – IRP Document

Show:

* This document open in GitHub
* Your name visible
* Current date visible

## Screenshot 24 – ICO Notification Chain

Show:

* T+0 to T+72 hour breach notification timeline
* Named roles (Incident Lead, CTO, DPO, ICO)

---

**Document End**
