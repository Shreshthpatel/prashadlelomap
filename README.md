# Jabalpur Bhandara

A community platform for discovering and submitting Bhandara events in Jabalpur, Madhya Pradesh.

## Security
The browser may contain a Supabase publishable/anon key. This is expected for a Supabase frontend and is **not** a service-role secret.

Never commit:
- Supabase service-role/secret keys
- Database passwords
- GitHub tokens
- Private API credentials

All privileged actions, especially Bhandara approval/removal, must be protected by Supabase Row Level Security (RLS).

## Stack
- HTML/CSS/JavaScript
- Supabase Auth, Postgres and Storage
- Leaflet + OpenStreetMap

## Running
Open `index.html` through a static web host or local HTTP server.

## Configuration
The Supabase project URL and publishable key are configured in the frontend. Rotate the publishable key if it is ever exposed as a secret elsewhere; do not replace it with a service-role key.
