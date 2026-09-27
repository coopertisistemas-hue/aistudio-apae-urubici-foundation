# Authentication and RBAC

## Public Site
Public users do not require login for normal browsing, donation initiation, contact or approved public forms unless a future workflow requires it.

## Admin
Authentication required.

## Initial role concepts
- PLATFORM_ADMIN: Urubici Connect technical administration.
- APAE_ADMIN: broad institutional administration.
- EDITOR: content and publication within authorized scope.
- FINANCE: donations/payment visibility with limited editorial rights.
- REVIEWER: moderation/review actions if needed.
- READ_ONLY: audit/support visibility when appropriate.

## Rules
- permissions, not UI hiding, enforce authorization;
- least privilege;
- no shared generic administrator account as final operating model;
- sensitive operations should be auditable;
- role matrix must be finalized before production.
