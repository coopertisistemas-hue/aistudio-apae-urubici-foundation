# APAE Urubici Foundation

Canonical product, design, content, UX, data, architecture, governance and quality specification for the APAE Urubici digital platform.

## Repositories

- Foundation: `aistudio-apae-urubici-foundation`
- Public Site: `aistudio-apae-urubici-site`
- Admin: `aistudio-apae-urubici-admin`

## Authority

Foundation is the source of truth. Site and Admin are implementation surfaces.

Authority order:
1. Foundation
2. Surface-specific Readdy context
3. Readdy execution instructions
4. Implementation code

## Documentation index

See [docs/INDEX.md](docs/INDEX.md) for the full map of Foundation documents. Deferred decisions are tracked in [docs/00-governance/DEFERRED_DECISIONS.md](docs/00-governance/DEFERRED_DECISIONS.md).

## Current baseline

**W00C — Independently Audited Foundation Baseline**

The Foundation now covers:
- governance and Definition of Done;
- digital discovery and benchmark;
- product vision, scope, audiences, journeys and requirements;
- public sitemap, homepage and content taxonomy;
- design principles, layout/component/media/motion rules;
- mobile-first and accessibility requirements;
- content strategy, editorial model, voice/tone and SEO/AEO;
- domain/data/consent/privacy model;
- Supabase, Auth/RBAC, Storage and Edge Function architecture;
- donations, CRM, campaigns, projects, testimonials, partners, transparency and social foundations;
- Portal Urubici, payments, email, WhatsApp and Meta integration contracts;
- mobile, accessibility, performance, security and production certification gates;
- delivery roadmap.

**Independent Foundation Audit**

The W00C baseline has been independently audited (see [docs/12-delivery/W00C_FOUNDATION_INDEPENDENT_AUDIT_REPORT.md](docs/12-delivery/W00C_FOUNDATION_INDEPENDENT_AUDIT_REPORT.md)): no P0 blockers, no unresolved contradictions, certified for entry into W01.

## Important pending institutional decisions

Final brand assets, exact palette, typography, current leadership, service inventory, validated impact metrics, partners, payment details, approved media/consents and official transparency content must be validated with APAE Urubici before production publication.

## Readdy

Readdy works directly on `main` in Site/Admin repos. `main` is therefore an authoring surface and must not be interpreted as production certification.
