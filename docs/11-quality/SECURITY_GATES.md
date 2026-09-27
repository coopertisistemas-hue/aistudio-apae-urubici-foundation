# Security Gates

## Required checks
- no secrets in client bundles/repository;
- RLS reviewed;
- privileged Edge Functions authenticate/authorize;
- webhook signatures verified;
- file upload validation;
- safe public/private storage policies;
- input validation;
- anti-abuse on public forms;
- least-privilege roles;
- dependency/security review;
- production environment variables verified.

## Financial flows
Payment state is authoritative only when confirmed through trusted provider/server paths.

## Logging
Do not leak credentials, tokens or unnecessary PII.
