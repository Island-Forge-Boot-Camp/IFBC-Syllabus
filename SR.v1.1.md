# Island Forge Senior Engineering Deepening Program  
**Senior Engineer Cohort – Version 1.1**  
_Date: 1 May 2025_

This curriculum bridges the gap between autonomous Mid-level engineers and the Leadership Launchpad for Staff.  Graduates become technical pillars who design multi-service systems, guard production reliability, and mentor juniors.

---

## Section 3 — Senior Engineering Program (16 Weeks)

**Objective:** Develop engineers who can own end-to-end architecture for a product slice (frontend + backend + DevOps), lead incident response, and begin managing small teams.

**Format:**  
* **Weeks 1-8:** Advanced labs & workshops (2 × 3-hr instructor sessions per week, plus lab homework).  
* **Weeks 9-15:** Embedded as Tech Lead on a live Island Forge client project (shadowed by a Staff mentor).  
* **Week 16:** Capstone delivery & defence.

| Week | Key Focus                  | Core Objectives                                                                    | Required Deliverables                               |
|------|----------------------------|------------------------------------------------------------------------------------|-----------------------------------------------------|
| 1    | **Architectural Patterns** | Hexagonal • DDD • Event-driven; choose best fit & justify trade-offs               | Architecture decision record (ADR)                 |
| 2    | **Advanced API Design**    | gRPC vs. REST • Versioning • Auth delegation (OAuth2 / OIDC)                       | Public API spec + Postman collection                |
| 3    | **Observability Deep-Dive**| OpenTelemetry tracing • Distributed log correlation                                | Trace + log correlation demo in Grafana             |
| 4    | **Reliability Engineering**| SLO maths • Error budgets • Alert fatigue cures                                    | SLO doc + pager playbook                            |
| 5    | **Security Hardening**     | OAuth threat patterns • Secrets rotation • GitHub Dependabot, Trivy scans          | Hardened Dockerfile + security scan pass            |
| 6    | **Data Layer Mastery**     | CQRS + Event Sourcing • Zero-downtime migrations                                   | Migration PR + rollback demo                        |
| 7    | **FinOps for Engineers**   | Cost-per-feature metrics • AWS Savings Plans • GPU/ML cost controls                | Cost dashboard + 10 % monthly saving proposal       |
| 8    | **Mentorship & Code Review**| Effective feedback (SBI) • Pairing anti-patterns                                   | Two recorded code-review sessions (video)           |
| 9-15 | **Tech-Lead Residency**    | Lead a two-sprint feature; estimate stories; run stand-ups; incident commander     | Feature shipped; post-incident review; team NPS ≥ 8 |
| 16   | **Capstone & Panel Demo**  | Present architecture, SLOs, FinOps wins to Staff panel                             | **Senior Engineer Badge**                           |

---

## Assessment & Promotion

| Passing Gate | Requirement                                                     |
|--------------|-----------------------------------------------------------------|
| **Lab Scores**      | ≥ 80 % weighted average across Weeks 1-8 labs            |
| **Capstone Panel**  | Panel score ≥ 75 % (architecture clarity, cost reasoning)|
| **Client NPS**      | ≥ 8 / 10 from project team & client PM                   |
| **Incident Drill**  | Pass live SEV-2 simulation within target MTTR           |

- One re-take opportunity per failed component (within 45 days).  
- Badge issued via GitHub Actions → Credly.  
- Senior graduates become **Staff-track eligible** after three months as Tech Lead on billable work.

---

© 2025 Island Forge. All rights reserved.
