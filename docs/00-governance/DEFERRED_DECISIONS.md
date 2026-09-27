# Deferred Decisions Register

Single consolidated register of decisions deliberately deferred by the Foundation.

These are **not omissions**. They are decisions that require institutional validation, design finalization or a downstream technical contract, and must remain explicitly deferred until their owner resolves them. Nothing here may be fabricated or silently assumed during implementation.

Status legend: `OPEN` (not yet resolved) · `RESOLVED` (decided and documented) · `SUPERSEDED`.

Owner legend: `APAE` (institutional validation) · `DESIGN` (design-system authority) · `PLATFORM` (Urubici Connect technical) · `LEGAL` (privacy/legal review).

## Institutional validation — target wave W01

| ID | Decision | Owner | Status | Source |
|----|----------|-------|--------|--------|
| DD-01 | Official brand assets / final institutional approval of revitalized digital logo | APAE / DESIGN | OPEN | Supplied APAE Urubici logo received as W01P source reference; BRAND_IDENTITY |
| DD-02 | Current leadership (diretoria) identities and roles | APAE | OPEN | README; ADMIN_ARCHITECTURE; sitemap `/apae/diretoria` |
| DD-03 | Current service / areas-of-work inventory | APAE | OPEN | W01R public evidence supports six validation axes; exact current service catalogue still requires APAE confirmation |
| DD-04 | Validated impact indicators (numbers) | APAE | OPEN | HOMEPAGE_SPEC §3; VOICE_AND_TONE |
| DD-05 | Official partners list and recognition scope | APAE | OPEN | PARTNERS module; HOMEPAGE_SPEC §11 |
| DD-06 | Donation/payment institutional details (accounts, PIX, provider accounts) | APAE / PLATFORM | OPEN | DONATIONS; PAYMENTS |
| DD-07 | Approved images/video and consent/rights provenance | APAE / LEGAL | OPEN | W01R requires social/media inventory and explicit reuse/consent review before production publication |
| DD-08 | Transparency documents approved for public disclosure | APAE | OPEN | TRANSPARENCY module |
| DD-09 | Final provider/account choices (payment, email, social, WhatsApp) | APAE / PLATFORM | OPEN | INTEGRATION_CONTRACTS |
| DD-10 | Portal Urubici editorial identities referenced in specs (e.g. the "Aline Liz" content axis) — confirm identity, ownership and approval-to-surface | APAE | OPEN | HOMEPAGE_SPEC §8 |
| DD-11 | Final LGPD/privacy policy, retention schedule, and `/privacidade` `/termos` `/acessibilidade` published content | LEGAL / APAE | OPEN | RETENTION_AND_PRIVACY; sitemap |
| DD-12 | Business success targets (donation conversion, recurring retention, cadence) — numeric goals | APAE | OPEN | MEASUREMENT_AND_SUCCESS_METRICS |
| DD-13 | Analytics tool choice and consent-banner copy | APAE / LEGAL | OPEN | CONSENT_MODEL; MEASUREMENT_AND_SUCCESS_METRICS |

## Design finalization — target wave W02

| ID | Decision | Owner | Status | Source |
|----|----------|-------|--------|--------|
| DD-20 | Final color palette / tokens | DESIGN | OPEN | Logo-derived W01P proposal palette defined in COLOR_SYSTEM; final W02 freeze pending |
| DD-21 | Final typography families | DESIGN | OPEN | Fraunces + Manrope adopted for W01P proposal; final W02 approval pending |
| DD-22 | Spacing/grid token freeze | DESIGN | OPEN | SPACING_AND_GRID |
| DD-23 | Final visual direction and content architecture approval | DESIGN / APAE | OPEN | ROADMAP W02 |

## Technical contracts — target waves W05–W08

| ID | Decision | Owner | Status | Source |
|----|----------|-------|--------|--------|
| DD-40 | Final role → permission matrix (incl. REVIEWER, READ_ONLY mapping) | PLATFORM | OPEN | AUTH_RBAC |
| DD-41 | Per-table RLS policy contracts | PLATFORM | OPEN | SUPABASE_ARCHITECTURE |
| DD-42 | Public read-data contract (public RLS views vs Edge API) for the Site | PLATFORM | OPEN | SUPABASE_ARCHITECTURE; EDGE_FUNCTIONS |
| DD-43 | Backup/DR expectations before financial/relationship data | PLATFORM | OPEN | SUPABASE_ARCHITECTURE |
| DD-44 | Observability / error-monitoring tooling contract | PLATFORM | OPEN | SOLUTION_ARCHITECTURE; PRODUCTION_CERTIFICATION |
| DD-45 | Data-subject-rights (access/deletion/portability) workflow | PLATFORM / LEGAL | OPEN | RETENTION_AND_PRIVACY; CONSENT_MODEL |

## Rule

An implementation agent (including Readdy) must treat every `OPEN` item as blocked for that specific decision. It may build the surrounding structure using placeholders/empty states, but must not invent the deferred value.
