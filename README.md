# 817Neon-PRD
# 817Neon — Product Requirements Document

**Version:** 1.0  
**Date:** April 2026  
**Status:** In Development  
**Launch Target:** June 2027

---

## What is 817Neon?

817Neon is a SaaS platform for NPA (Non-Performing Asset) lifecycle management built specifically for African banks.

Africa has $80 billion in non-performing assets sitting on bank balance sheets with almost no dedicated SaaS infrastructure to solve it. 817Neon is being built to be the category-defining solution.

---

## The Problem

African banks face three critical NPA challenges:

**1. Detection**
NPAs are identified too late. By the time a loan is classified as non-performing, recovery probability has already dropped significantly. Most banks rely on manual spreadsheet tracking.

**2. Management**
No unified system for tracking NPA lifecycle — from early warning signals to full default. Teams use disconnected tools, WhatsApp groups, and Excel files.

**3. Recovery**
Recovery workflows are manual, inconsistent, and undocumented. No audit trail. No performance metrics. No predictive capability.

---

## The Solution

817Neon provides three core modules:

### Module 1 — DETECT
Early warning system for loan default risk.

- Real-time monitoring of loan health indicators
- Automated risk scoring per account
- Alert system for relationship managers
- Dashboard showing portfolio risk distribution

### Module 2 — MANAGE
Centralised NPA lifecycle management.

- Single view of all non-performing accounts
- Stage tracking — from early warning to write-off
- Document management per account
- Team assignment and task management
- Communication log with borrowers
- Regulatory reporting templates

### Module 3 — RECOVER
Recovery workflow automation.

- Recovery action plans per account
- Legal process tracking
- Collateral management
- Recovery performance metrics
- Predictive recovery probability scoring

---

## Target Market

**Primary:** African banks — Tier 2 and Tier 3
**Geography:** Nigeria, Kenya, Ghana, South Africa, Ethiopia — Phase 1
**Decision maker:** Chief Risk Officer, Head of Credit
**User:** Risk managers, relationship managers, recovery officers

---

## Pricing Model

SaaS — Annual subscription per bank
- Pricing based on loan book size
- Per module or full platform
- Implementation and onboarding fee
- Annual support contract

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React.js — web application |
| Backend | Python FastAPI |
| Database | PostgreSQL |
| Cloud | AWS Africa (Cape Town region) |
| Authentication | Auth0 |
| Reporting | Python + ReportLab |

---

## Key Metrics

| Metric | Target |
|---|---|
| NPA detection time | Reduce by 60% |
| Recovery rate | Improve by 25% |
| Regulatory reporting time | Reduce by 80% |
| Manual data entry | Eliminate completely |

---

## Roadmap

| Phase | Timeline | Deliverable |
|---|---|---|
| Phase 1 | Apr-Jun 2026 | Core architecture and database design |
| Phase 2 | Jul-Sep 2026 | Detect module — MVP |
| Phase 3 | Oct-Dec 2026 | Manage module — MVP |
| Phase 4 | Jan-Mar 2027 | Recover module — MVP |
| Phase 5 | Apr-May 2027 | Beta testing with 2 African banks |
| Phase 6 | Jun 2027 | Public launch |

---

## Competitive Advantage

- **First mover:** No dedicated NPA SaaS for African banks exists
- **African-specific:** Built for African regulatory environments
- **Affordable:** Priced for Tier 2 and 3 banks — not enterprise pricing
- **Simple:** Designed for teams transitioning from spreadsheets

---

*Built by 817Nine. Zero external capital. June 2027.*
