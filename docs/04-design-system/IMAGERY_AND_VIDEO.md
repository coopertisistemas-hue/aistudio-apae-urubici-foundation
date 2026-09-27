# Imagery and Video

## Direction
Authentic, dignified, warm and documentary rather than staged or synthetic.

## Repository-managed media
Permanent brand/design assets and approved hero media may live in Git.

## Dynamic media
Editorial media uploaded by staff should live in managed object storage.

## Consent, Rights and Provenance
For each sensitive asset, record:
- source/owner;
- subject/usage authorization;
- permitted channels;
- validity/restrictions;
- publication status (`REFERENCE_ONLY`, `INSTITUTIONAL_OWNERSHIP_LIKELY_BUT_UNCONFIRMED`, `APPROVED_FOR_PROPOSAL`, `APPROVED_FOR_PUBLICATION`).

Public availability is not permission to republish:
- Social posts and public news photos may serve as *reference candidates* only.
- Under no circumstances may public social photography or identifiable beneficiary photos be hotlinked, downloaded, or committed to production without explicit written institutional consent.

## Mobile-First Visual Selection & Focal Control
- Visual selection must be executed mobile-first (primary 390px viewport).
- Every photograph or illustration must specify per-image focal coordinates (`mobileObjectPosition`, `tabletObjectPosition`, `desktopObjectPosition`) to guarantee subjects are not cropped improperly on mobile viewports.
- Non-critical imagery below the fold must lazy-load with reserved aspect-ratio boxes to prevent layout shifts (CLS).


## Hero video
- separate desktop/mobile variants;
- optimized codec/bitrate;
- poster image;
- muted autoplay when used;
- no dependency on audio for meaning;
- reduced-motion fallback;
- captions/transcript when speech conveys meaning;
- Admin replaceable when configured as dynamic.

## AI imagery
Do not use synthetic depictions of beneficiaries as if they were real institutional documentation.
