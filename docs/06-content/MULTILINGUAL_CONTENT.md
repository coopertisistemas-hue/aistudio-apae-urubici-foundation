# Multilingual Content Standard

Status: ACTIVE PRODUCT REQUIREMENT

The APAE Urubici public website must be multilingual by default.

## Supported locales

- Portuguese (Brazil): `pt-BR` — default
- English: `en`
- Spanish: `es`
- German: `de`

## Experience requirements

- A visible language selector must be available in the desktop header.
- The language selector must also be available in mobile navigation.
- The selected language should persist across navigation where technically practical.
- Language switching must be keyboard-accessible and understandable to assistive technology.
- Do not use country flags as the only language identifier.
- Prefer clear language labels/codes such as PT, EN, ES, DE with accessible names.

## Content architecture

All user-facing content should be structured so translated variants can be supplied without duplicating layout logic.

Future Admin-managed content should support locale-aware fields or translation records rather than hardcoded translated pages.

## Proposal phase

During W01P, Portuguese may remain the only complete editorial language while the architecture and selector support all four locales.

Untranslated proposal content must degrade gracefully; do not fabricate institutional translations if source content itself is not validated.

## SEO/AEO

When translated routes/content become publishable:
- use locale-aware metadata;
- provide appropriate `hreflang` relationships;
- preserve canonical logic;
- translate structured content and social metadata consistently.

## Quality

Translations must preserve:
- dignity;
- factual integrity;
- accessibility;
- institutional tone;
- terminology around disability and inclusion.

Machine-assisted translation may support drafting, but institutional/publication review remains required for final production content.
