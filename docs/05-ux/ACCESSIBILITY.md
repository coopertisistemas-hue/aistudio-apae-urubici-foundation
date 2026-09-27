# Accessibility

Accessibility is P0 and intrinsic to the institution's mission.

The APAE Urubici platform must be designed for real use by people with disabilities, families, caregivers, professionals, older adults and the broader community.

## Baseline

Target WCAG 2.2 AA behavior wherever applicable.

Use Brazilian digital-accessibility guidance (including eMAG) as complementary implementation reference.

Accessibility is not considered complete through a widget, automated scanner or accessibility overlay.

## Core requirements

- semantic HTML and landmark structure;
- complete keyboard operability;
- predictable focus order;
- visible focus;
- sufficient contrast;
- scalable text;
- 200%/400% zoom and reflow without loss of functionality;
- accessible names and descriptions;
- explicit form labels;
- clear error identification and recovery;
- useful human-authored alt text;
- captions/transcripts for relevant audio/video;
- touch targets suitable for mobile and motor impairments;
- orientation flexibility;
- reduced-motion support;
- no autoplay with sound;
- no color-only meaning;
- no hover-only functionality;
- accessible status/error announcements where dynamic UI requires them;
- correct document/page language and language-of-parts behavior.

## Cognitive accessibility

Because the institutional audience may include people with intellectual or cognitive disabilities, the Site must actively reduce unnecessary cognitive load.

Prefer:
- direct language;
- short paragraphs;
- one main idea per content block;
- descriptive headings;
- consistent navigation;
- predictable controls;
- clear CTA wording;
- icon + text rather than icon-only meaning;
- progressive disclosure for complex tasks;
- simple confirmation and recovery patterns;
- stable layouts;
- limited simultaneous choices.

Avoid:
- infantilized language;
- unexplained jargon;
- dense walls of text;
- automatic carousels;
- flashing or continuous decorative motion;
- complex interactions that depend on memory;
- unnecessary time limits.

A future "simple reading" editorial treatment may be evaluated for selected complex content. It must never be presented as childish content.

## Visual accessibility

- yellow is an accent, not a default body-text color on light surfaces;
- brand green/yellow combinations must be contrast-tested;
- links and controls must remain identifiable without color alone;
- typography must remain legible at small screen sizes;
- images containing text should be avoided where HTML text can be used;
- essential text must never be embedded only inside images.

## Screen-reader accessibility

Key journeys must be tested with semantic structure suitable for screen readers.

Verify:
- heading hierarchy;
- skip links;
- landmarks;
- button/link semantics;
- names for icon controls;
- menu/dialog expanded state;
- dynamic language changes;
- alt text;
- form errors and instructions;
- focus after route/modal/state transitions.

## Documents and transparency accessibility

Transparency and institutional documents are part of the accessibility contract.

Requirements:
- whenever feasible, publish accessible HTML alongside downloadable documents;
- PDFs intended for public use must be tagged, searchable and structured for assistive technology;
- preserve logical reading order, headings, lists, tables, document language and meaningful link text;
- scanned-image-only PDFs are not acceptable as the sole public format for essential information;
- if a legacy document cannot yet be remediated, provide an accessible summary/HTML alternative and identify the limitation;
- downloadable statutes, reports, financial statements, notices and policies must be included in accessibility QA.

## WCAG 2.2 criteria to explicitly verify

In addition to the general WCAG 2.2 AA target, key journeys must explicitly verify:
- 2.4.11 Focus Not Obscured (Minimum);
- 2.5.8 Target Size (Minimum) — use at least a 24 x 24 CSS-pixel target or equivalent spacing exception where the criterion permits;
- 3.2.6 Consistent Help where help mechanisms exist;
- 3.3.7 Redundant Entry;
- 3.3.8 Accessible Authentication (Minimum) for authentication journeys.

## Media accessibility

When real APAE media is introduced:
- videos require captions;
- relevant spoken informational content should have transcript support;
- autoplay audio is prohibited;
- controls must be keyboard accessible;
- decorative media should not generate unnecessary screen-reader noise.

## Libras and deaf access

Libras support is a planned institutional-accessibility decision, not an optional decorative widget.

The production plan must evaluate:
- which high-value institutional journeys/content require Libras;
- whether human-produced Libras video is appropriate;
- caption quality and transcript availability;
- legal and institutional context under Brazilian accessibility and Libras requirements, including Lei 10.436/2002 and Decreto 5.626/2005.

Automated translation widgets alone do not satisfy accessibility or institutional-quality requirements.

## Multilingual accessibility

Supported locales:
- pt-BR;
- en;
- es;
- de.

Language selector requirements:
- keyboard accessible;
- current language clearly communicated;
- no flags as the only language representation;
- correct `lang` metadata;
- accessible names in each language.

## Content

Avoid patronizing, infantilizing, pity-driven or sensational language about disability.

Prefer rights-based and person-centered communication:
- dignity;
- autonomy;
- participation;
- accessibility;
- belonging;
- rights;
- human development.

## Testing

Automated checks are necessary but not sufficient.

Before production certification, key journeys require:
- keyboard-only review;
- mobile touch review;
- screen-reader review;
- contrast review;
- zoom/reflow review;
- reduced-motion review;
- multilingual selector review;
- form validation/error review;
- manual review by people familiar with disability/accessibility needs.

For key public journeys, production certification must include planned validation with users and/or reviewers with relevant assistive-technology, cognitive-accessibility or disability expertise; this is not optional when the journey is essential.

Accessibility findings are release blockers when they prevent access to essential institutional information or key journeys.


## Accessibility as visible product language

For the next Site rebuild, accessibility must shape the experience visibly, not sit behind the interface as a compliance layer.

Design for:
- people with intellectual/cognitive disabilities;
- people with low digital literacy;
- screen-reader users;
- keyboard-only users;
- people using zoom/reflow;
- people with motor limitations;
- deaf/hard-of-hearing users;
- families under stress who need quick orientation.

Experience requirements:
- plain-language entry points for essential journeys;
- short content blocks and clear section purpose;
- large, obvious interactive targets;
- no time-pressure interactions;
- reduced-motion parity;
- predictable navigation;
- no essential meaning carried by decorative motion;
- icon + text where icons materially aid comprehension;
- future audio and strategic Libras support as governed enhancements;
- no separate, inferior "accessible version".

The preferred pattern is universal accessible design with optional supportive modalities.
