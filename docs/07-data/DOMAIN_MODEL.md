# Domain Model

## Core domains
- Institution
- Content
- Projects
- Campaigns
- Events
- Testimonials
- Partners
- Transparency
- Contacts/CRM
- Donations
- Recurrences
- Media
- Consent
- Users/Roles
- Integrations

## Key relationships
- Project may have many partners, articles, media and campaigns.
- Campaign may receive many donations.
- Donor may have many donations and optional relationship consent.
- Testimonial may be linked to invitation/source and publication consent.
- Content may have source/origin and distribution flags.
- Partner may support many projects.
- Media must retain provenance/rights metadata where relevant.

## Principle
Model business meaning explicitly rather than storing critical behavior in opaque JSON blobs.
