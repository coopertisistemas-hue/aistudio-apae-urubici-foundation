# Solution Architecture

## Surfaces
Public Site + Admin/CMS + Supabase + Storage + Edge Functions + external providers.

## High-level flow
Admin writes governed data → Supabase → approved/public data exposed to Public Site through appropriate access/API contracts.

External integrations may include:
- payment providers;
- email provider;
- Portal Urubici;
- Meta/Instagram/Facebook;
- future WhatsApp provider.

## Principles
- least privilege;
- no service-role secrets in client code;
- provider abstraction for payments;
- graceful degradation for external content;
- explicit environment separation;
- migration-driven database changes;
- observable production-critical flows.
