# Delivery Governance

## Repository model

- `aistudio-apae-urubici-foundation`: canonical specification and governance.
- `aistudio-apae-urubici-site`: public site implementation.
- `aistudio-apae-urubici-admin`: Admin/CMS implementation.

## Authority order

1. Foundation
2. Surface-specific Readdy context
3. Readdy execution instructions
4. Implementation code

If implementation conflicts with Foundation, implementation must be corrected or Foundation must be explicitly revised first.

## Readdy constraint

Readdy works on `main`. Therefore:
- `main` is an authoring surface;
- `main` is not automatically production-certified;
- production requires independent validation and certification;
- no silent production promotion is allowed.

## Wave rules

Each wave must define scope, authority, evidence, validation, stop conditions and closure criteria.

Foundation changes that alter product behavior must be propagated to Site/Admin context snapshots before implementation is considered aligned.

## Closure

A wave closes only after:
- scope delivered;
- evidence recorded;
- affected gates passed;
- unresolved issues classified;
- Foundation/context synchronization completed;
- production certification completed when applicable.
