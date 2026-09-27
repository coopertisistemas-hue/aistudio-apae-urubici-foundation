# Data Model — Initial Contract

This is a logical model. Physical schema may evolve through reviewed migrations.

## Suggested entities
- profiles
- roles / memberships
- site_settings
- homepage_sections
- hero_config
- impact_metrics
- service_areas
- projects
- campaigns
- content_items
- content_topics
- events
- testimonials
- testimonial_invitations
- partners
- project_partners
- transparency_documents
- contacts
- contact_interests
- marketing_consents
- donors
- donations
- donation_recurrences
- payment_events
- email_events
- media_assets
- integration_settings
- audit_events

## Common publication fields
Where applicable:
- id
- status
- slug
- created_at
- updated_at
- published_at
- created_by
- updated_by

## Rules
- use stable identifiers;
- enforce status values;
- preserve audit-relevant timestamps;
- separate consent evidence from marketing profile convenience fields;
- avoid storing secrets in public/client-readable records.
