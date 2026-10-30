# SearchMC
`npm install && npm run dev` · `npm test` (Node ≥22.6). Premium data: official Mojang API. Avatars: Crafatar (external, replaceable in `app/player/[query]/page.tsx`).
No Premium has no official source: needs your own DB (PostgreSQL) of observed/user-submitted names. Rate limit & cache are in-memory (use Redis for multi-instance).
