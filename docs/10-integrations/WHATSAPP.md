# WhatsApp

## Initial use
The system must support sending a testimonial invitation link manually through WhatsApp without requiring WhatsApp API integration.

## Future integration
Potential uses:
- opted-in institutional communication;
- volunteer/partner follow-up;
- campaign communication;
- invitation links.

## Rules
- require appropriate consent for proactive marketing;
- avoid exposing sensitive data in message URLs;
- invitation tokens must be non-guessable and revocable/expirable where appropriate;
- do not make WhatsApp the only path for essential institutional information.

## Public inbound click-to-chat CTA
A floating or fixed inbound WhatsApp contact CTA is authorized on the public site under the following rules:
- WhatsApp is a secondary contact path, never the only path for essential institutional information;
- the destination telephone number must be institutionally validated before publication;
- no sensitive data, personal identifiers, or security tokens in URL or pre-filled message;
- must use accessible semantic link or button elements;
- minimum practical interactive target size around 44x44px;
- visible keyboard focus states;
- mobile safe-area support (respecting device notches and system bars);
- must not obscure navigation, footer links, or critical page content;
- reduced-motion safe (no aggressive bounce, pulse, or looping animations);
- may be hidden on 404 recovery pages or while the mobile menu is active;
- proposal mode may render only a disabled/placeholder state when the institutional number is not yet validated;
- proactive outbound marketing still requires appropriate consent.
