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

## Media accessibility

When real APAE media is introduced:
- videos require captions;
- relevant spoken informational content should have transcript support;
- autoplay audio is prohibited;
- controls must be keyboard accessible;
- decorative media should not generate unnecessary screen-reader noise.

Libras may be evaluated for high-value institutional content. Automated translation widgets alone do not satisfy this requirement.

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
- manual review by people familiar with disability/accessibility needs where feasible.

Accessibility findings are release blockers when they prevent access to essential institutional information or key journeys.
