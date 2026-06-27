# River CRM

A single-file CRM tool with Supabase backend, Google Sheets sync, lead management, and role-based access control.

## Live URLs

- **Kimi Deploy**: https://nzfm345topeqg.kimi.page
- **GitHub Repo**: https://github.com/shareekads-collab/river-crm

## Features

- **Dashboard** — Pipeline tabs, sortable columns, search, custom columns
- **Analytics** — Full metrics, charts, conversion funnel
- **Settings** — Column mapping, visible columns, user management
- **Google Sheets Sync** — Auto-import leads, sync columns, detect new/deleted columns
- **Auth** — Email-only login, role-based access (admin/user)

## Deploy to Vercel

Click the button below or go to [vercel.com](https://vercel.com) → Import from GitHub → select this repo.

## Supabase Config

1. Create a Supabase project
2. Run the migration in `supabase/migration.sql`
3. Add your `SB_URL` and `SB_KEY` to the config in `index.html`

## Login

- **Owner**: `shareekads@gmail.com`

## Tech Stack

- Single-file HTML + Vanilla JavaScript
- Supabase REST API (Postgres)
- Google Sheets API v4
- Vercel Static Hosting
