# Healthcare FWA & Claims Review Analytics

> SQL and Python analysis for Healthcare Fraud, Waste & Abuse (FWA) detection, Medicare/Medicaid claims review, and fraud pattern identification

---

## Overview

This repository contains analytical tools, SQL queries, and Python scripts designed to support Healthcare Fraud, Waste & Abuse (FWA) investigations and Medicare/Medicaid claims review processes. The work here reflects real-world fraud detection methodologies used by SIU analysts, claims reviewers, and compliance professionals.

---

## Contents

### SQL Queries
- Claims billing anomaly detection (unbundling, upcoding, duplicate billing)
- Provider outlier analysis vs. peer benchmarks
- Beneficiary utilization pattern flags
- High-frequency claim submission detection
- Date-of-service overlap and impossible day identification

### Python Scripts
- Statistical anomaly detection on claims data
- Automated flagging of high-risk providers
- Data cleaning and normalization pipelines
- Summary reporting for FWA case documentation

---

## Key FWA Indicators Addressed

| Fraud Indicator | Detection Method |
|---|---|
| Duplicate claims | SQL deduplication logic |
| Upcoding / unbundling | CPT/procedure code analysis |
| Impossible service dates | Date overlap queries |
| Provider outliers | Statistical benchmarking |
| Beneficiary sharing patterns | Network analysis flags |
| Ghost billing | Service vs. eligibility matching |

---

## Tools & Technologies

- **SQL** (MySQL, PostgreSQL compatible)
- **Python** (pandas, numpy, scipy)
- **Excel / Power Query** for reporting
- Aligned with **CMS FWA guidelines** and **HIPAA compliance** standards

---

## Related Repositories

- [fraud-detection-sql](https://github.com/Spearska/fraud-detection-sql) — SQL queries for transaction and account fraud
- [transaction-anomaly-detection](https://github.com/Spearska/transaction-anomaly-detection) — Statistical anomaly detection in Python
- [fraud-rules-engine](https://github.com/Spearska/fraud-rules-engine) — Rule-based decision trees for fraud detection

---

## About the Author

**K.A. Spears** | Fraud Investigator | FWA & SIU Analyst | Claims Review | 20+ Years Experience

- LinkedIn: [linkedin.com/in/kaspears](https://linkedin.com/in/kaspears)
- AML Certified | FWA Certified | ACA Certified
- 100% Remote | Open to Fraud Analyst / Claims Analyst roles
