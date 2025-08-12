
# Real Estate CRM (Supabase + Next.js)

A clean, minimal, **error-free** starter you can run instantly on Supabase and deploy to Vercel.

## 1) Create Supabase project
- Go to **Project Settings → API** and copy the project URL and anon key.
- In Supabase **SQL Editor**, run the contents of `supabase/db.sql` (execute all). No "IF NOT EXISTS" policies are used.

## 2) Configure the app
- Copy `.env.example` to `.env.local` and paste your `NEXT_PUBLIC_SUPABASE_URL` and `NEXT_PUBLIC_SUPABASE_ANON_KEY`.

## 3) Run locally
```bash
npm i
npm run dev
```
Open http://localhost:3000

## 4) Deploy (Vercel)
- Push this repo to GitHub.
- Import into Vercel → Set the two env vars above.
- Build & deploy.

## 5) First-time setup
- Open `/auth` in the deployed app, sign in via email magic link.
- Click **Create Org & Profile (RPC)** once to become admin of your org.
- Start adding leads!

## Features
- Org/agent model with **Row Level Security**
- Leads CRUD with funnel statuses and **WhatsApp deep-link**
- **CSV import** (up to 1000 rows at once)
- **Follow-up reminders** page for due/overdue items

## Tables
- `orgs`, `user_profiles`, `leads`

