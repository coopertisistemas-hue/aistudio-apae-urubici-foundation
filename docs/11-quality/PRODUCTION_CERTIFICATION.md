# Production Certification

`main` is not certification.

## Production candidate
Must identify exact commit/deployment.

## Required evidence
- Foundation baseline/version;
- Site/Admin commit SHAs;
- migration state;
- environment configuration checks;
- mobile smoke;
- desktop smoke;
- accessibility gates;
- payment flow tests when enabled;
- email tests when enabled;
- Admin auth/RBAC checks;
- public content integrity;
- Portal integration fallback;
- error monitoring/log review.

## Verdict
Use explicit PASS / HOLD / FAIL with blockers.

## Closure
Only PASS permits declaring the product/feature production-certified.
