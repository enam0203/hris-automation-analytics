# System Scope: Automated People Operations Platform

## Purpose
This project simulates a lightweight HRIS and People Operations system designed to manage
employee lifecycle events, automate compliance workflows, and generate workforce analytics.

The system is intentionally scoped to reflect how internal People Ops, HRIS, and Analytics
teams design infrastructure — not a full production HRIS.

---

## In Scope (What This System Does)

### Employee Lifecycle
- Onboarding
- Role changes (lateral moves)
- Promotions
- Manager changes
- Leaves of absence (LOA)
- Terminations

### Automation
- Event-driven workflows triggered by lifecycle changes
- Task generation for HR, IT, managers
- Compliance training assignment and reminders
- Audit logging of system actions

### Analytics
- Headcount and lifecycle trends
- Task completion and SLA metrics
- Training compliance risk
- Attrition risk modeling (statistical, not deterministic)

---

## Out of Scope (Intentionally Excluded)
- Payroll calculations
- Benefits enrollment rules
- Performance management ratings
- Time tracking
- Employee self-service UI beyond basic forms
- External system integrations (mocked only)

---

## Design Principles
- Append-only event history
- Automation before dashboards
- Auditability over realism
- Explainable analytics over black-box models
