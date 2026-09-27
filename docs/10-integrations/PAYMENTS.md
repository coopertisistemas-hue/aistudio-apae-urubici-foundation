# Payments

## Product requirement
Support a provider-independent donation architecture.

## Target capabilities
- one-time contribution;
- recurring contribution where provider supports it;
- PIX;
- card;
- PayPal;
- Stripe;
- future provider addition.

## Security
- never trust client confirmation as payment truth;
- confirm using provider APIs/webhooks;
- verify webhook signatures;
- idempotent event handling;
- do not store raw card credentials.

## Admin
Unified donation view regardless of provider:
- amount;
- donor;
- provider;
- external reference;
- status;
- recurrence;
- campaign;
- timestamps;
- thank-you status.

## Important
Provider-specific capabilities and fees must be revalidated at implementation time.
