# OpenSecure Bank — GRC Compliance Audit
### NIST Cybersecurity Framework (CSF) | SimpleRisk | June 2026

---

## Project Overview

End-to-end GRC compliance audit simulation for a fictional financial institution, **OpenSecure Bank**, conducted using **SimpleRisk** — an enterprise risk management platform used by real organizations worldwide.

This project mirrors the exact workflow a GRC Analyst performs in industry:
- Building and classifying an asset inventory
- Mapping security controls to a compliance framework
- Scoring control maturity and identifying gaps
- Assessing and scoring organizational risks
- Planning mitigations with ownership and target dates
- Defining compliance tests and initiating audits
- Producing a formal executive audit report

---

## Tools & Frameworks Used

| Tool / Framework | Purpose |
|---|---|
| SimpleRisk (Community Edition) | GRC platform — risk, control, and compliance management |
| NIST Cybersecurity Framework (CSF) v1.1 | Compliance framework for control mapping |
| Microsoft Word | Formal audit report |
| Microsoft Excel | Risk register and control maturity scorecard |
| Docker | Local deployment of SimpleRisk |

---

## Audit Scope

| Category | Count |
|---|---|
| Assets Inventoried | 10 |
| Security Controls Assessed | 20 |
| Controls Passing | 15 |
| Controls Failing | 5 |
| Risks Identified | 10 |
| High Severity Risks | 3 |
| Medium Severity Risks | 6 |
| Low Severity Risks | 1 |

---

## Key Findings

### Critical Gaps Identified (Status: Fail)

| Control ID | Control Name | NIST Function | Current Maturity |
|---|---|---|---|
| DE.CM-1 | SIEM Monitoring | Detect | Not Performed |
| PR.AC-7 | Multi-Factor Authentication | Protect | Not Performed |
| DE.CM-4 | Intrusion Detection System | Detect | Not Performed |
| DE.AE-1 | Anomaly Detection Policy | Detect | Not Performed |
| RC.IM-1 | Lessons Learned Documentation | Recover | Not Performed |

### Top 3 High Severity Risks

| Risk ID | Risk Description | Score | Priority |
|---|---|---|---|
| RISK-001 | Unauthorized Access to Customer Database | 10 | Critical |
| RISK-003 | Phishing Attack on Employees | 8 | High |
| RISK-009 | VPN Credential Compromise | 8 | High |

---

## Deliverables

| File | Description |
|---|---|
| OpenSecure_Bank_GRC_Audit_Report.pdf | Full formal audit report with findings and recommendations |
| OpenSecure_Bank_Risk_Register.xlsx | Risk register and control maturity scorecard |
| Screenshots/ | Complete SimpleRisk workflow documentation |

---

## NIST CSF Coverage

| Function | Controls | Passing | Failing |
|---|---|---|---|
| Identify | 3 | 3 | 0 |
| Protect | 6 | 5 | 1 |
| Detect | 4 | 1 | 3 |
| Respond | 4 | 4 | 0 |
| Recover | 3 | 2 | 1 |
| **Total** | **20** | **15** | **5** |

---

## Overall Audit Conclusion

**Compliance Status:** Partially Compliant
**Overall Risk Posture:** High
**Next Audit Date:** December 22, 2026

The most critical remediation priorities are deploying a SIEM platform, enforcing MFA on all critical systems, and implementing IDS coverage across all network segments. Full remediation is targeted for completion by December 22, 2026.

---

*Prepared by: Ninad Patil | GRC Analyst | June 2026*
*This project was conducted as a portfolio simulation using SimpleRisk Community Edition. All data represents a fictional financial institution.*
