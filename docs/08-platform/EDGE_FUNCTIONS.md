# Edge Functions

## Expected use cases
- payment session/order creation;
- payment webhook handling;
- professional email dispatch;
- testimonial invitation issuance;
- Portal Urubici content integration/proxy when needed;
- protected export/integration operations;
- future social/WhatsApp provider interactions.

## Rules
- validate authentication/authorization where needed;
- validate input;
- never trust client-supplied payment status;
- verify webhook signatures;
- make webhook processing idempotent;
- keep secrets server-side;
- return safe errors;
- log operationally useful events without leaking secrets/PII.

## Public content
Do not add an Edge Function merely for architecture ceremony when safe RLS-backed reads are sufficient.
