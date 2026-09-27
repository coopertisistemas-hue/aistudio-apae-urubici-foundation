# Donations Module

## Goals

Support:
- one-time donation;
- recurring contribution;
- PIX;
- card/payment providers;
- future provider expansion.

## Provider strategy

The product should not be tightly coupled to one payment provider.

A provider abstraction should support, initially or progressively:
- PayPal;
- Stripe;
- PIX;
- future providers.

## Admin visibility

Authorized users should be able to view:
- donation amount;
- donor;
- provider;
- payment status;
- recurrence status;
- campaign attribution;
- timestamps;
- communication/thank-you status.

## Thank-you flow

Confirmed contributions should be eligible to trigger a professional automatic thank-you email.

## Relationship consent

Payment consent and marketing/relationship consent must be separate.
