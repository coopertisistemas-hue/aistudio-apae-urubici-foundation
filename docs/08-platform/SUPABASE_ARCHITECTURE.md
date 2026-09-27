# Supabase Architecture

## Responsibilities
- Postgres canonical application data;
- Auth;
- RLS;
- Storage for dynamic media/documents;
- Edge Functions;
- database triggers/functions only when justified.

## Client access
Public Site should read only explicitly public data.

Admin authenticated clients must operate under RLS whenever direct client access is used.

Privileged operations belong server-side/Edge Functions.

## Migrations
All schema, policy and function changes must be versioned through migrations.

## Environments
Development/test and production configuration must not share unsafe credentials or uncontrolled data.

## Backups
Production release planning must include recovery/backup expectations before accepting financial or relationship-critical data.
