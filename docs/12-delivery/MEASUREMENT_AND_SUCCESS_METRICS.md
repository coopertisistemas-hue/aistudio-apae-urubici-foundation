# Measurement and Success Metrics

## Purpose

Define **what** the platform measures and **how** measurement is governed, so product value (institutional reach, relationship growth, donations) can be evidenced without compromising privacy.

Numeric targets are institutional/business decisions and are **deferred** (see Deferred Decisions Register: DD-12). This document defines the measurement framework, not the goals themselves.

## Measurement principles

- Privacy-first: measurement must respect LGPD, data minimization and consent.
- No covert tracking or profiling (consistent with CRM module principles).
- Analytics that set non-essential cookies or identifiers require explicit consent (see CONSENT_MODEL).
- Prefer aggregate, non-identifying metrics for public-audience analytics.
- Measurement must never justify fabricated results.

## Metric categories (what to measure)

### Reach & content
- page/section engagement on key public journeys;
- article/news/project consumption;
- Inclusion & Human Development editorial engagement.

### Relationship & CRM
- form completion rates (contact, volunteer, partner);
- consent opt-in rate (relationship/marketing);
- relationship pipeline by type and follow-up status.

### Donations (business outcome)
- donation initiation → confirmation conversion;
- one-time vs recurring split;
- recurring supporter retention/churn;
- average and total confirmed contribution (derived from trusted payment data only);
- campaign attribution.

### Quality signals
- Core Web Vitals field data (see PERFORMANCE_GATES);
- accessibility issue trend;
- error/monitoring incident rate on production-critical flows.

## Governance

- Metric definitions must be stable and documented before a target is set against them.
- Donation/financial metrics derive only from confirmed provider/server-verified data.
- Dashboards for staff must not expose beneficiary-sensitive data.

## Deferred

- Concrete numeric targets and KPIs (DD-12).
- Analytics tool selection and consent-banner copy (DD-13).
