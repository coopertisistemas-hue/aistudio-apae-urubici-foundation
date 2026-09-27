# Testimonials Module

## Inputs

Testimonials may be created:
1. manually by authorized Admin users;
2. through a public site form;
3. through a unique invitation link sent by WhatsApp or email.

## Workflow

Submitted testimonials must be stored with status `pending`.

Publication requires moderation.

## Consent model

Consent choices must be recorded separately where applicable:
- publish testimonial text;
- display person's name;
- display photo;
- reuse on social channels.

The consent record must capture its version and timestamp.

## Suggested fields

- id
- invitation_id
- name
- relationship_to_apae
- testimonial_text
- photo_url
- source
- status
- consent_text
- consent_name
- consent_photo
- consent_social
- consent_version
- consented_at
- created_at
- reviewed_at
- reviewed_by
- featured_on_home
