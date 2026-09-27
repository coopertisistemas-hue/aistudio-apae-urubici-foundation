# Consent Model

## Principle
Consent must be specific, informed, auditable and separable by purpose.

## Testimonial permissions
Potentially separate:
- publish testimonial text;
- display name;
- display photo;
- reuse on social channels.

Record:
- consent version;
- timestamp;
- source;
- invitation when applicable;
- explicit values.

## Relationship marketing
Marketing/relationship consent is optional and separate from:
- donation processing;
- contact request;
- volunteer request;
- testimonial submission.

## Withdrawal
Architecture must support future withdrawal/suppression without rewriting historical payment records.

## Analytics and cookies
Non-essential analytics, tracking cookies/identifiers and third-party social embeds (e.g. Instagram/Facebook) must be implemented under the approved privacy/LGPD policy and must not load before the applicable consent/legal-basis decision has been satisfied.
- Strictly necessary functionality must not be gated behind optional analytics consent.
- Where consent is the approved basis, the consent state must be revocable.
- Tool choice, legal-basis implementation and consent-banner copy are deferred (see Deferred Decisions Register: DD-13).

## Sensitive context
Do not treat consent as a blanket license for all channels or indefinite reuse when the authorization does not support that scope.
