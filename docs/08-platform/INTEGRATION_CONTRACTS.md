# Integration Contracts

Each external integration must define:
- owner;
- purpose;
- data exchanged;
- authentication;
- retry behavior;
- failure behavior;
- observability;
- privacy implications;
- fallback;
- environment configuration.

## Required contracts
- Portal Urubici
- Payment provider(s)
- Email provider
- Meta/Instagram/Facebook when enabled
- WhatsApp when enabled

No integration should be implemented solely through undocumented frontend calls.
