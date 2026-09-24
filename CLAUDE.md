# InsightsHub

A team dashboard for primary and secondary research, pulling data from external sources.

## Status

Pre-scaffold: stack is decided, but no application code exists yet (repo only has this file + README). Once the app is scaffolded, update the "Commands" and "Structure" sections below with the real thing — don't leave this file describing an app that isn't there.

## Stack (decided)

- **Next.js (App Router) + TypeScript** — one repo for UI and simple API routes.
- **Deployed on Vercel** — gives teammates an automatic preview URL per PR.
- Data is pulled from external sources at runtime/build time (not hand-entered or stored locally) — likely via API routes acting as a thin proxy/aggregator.
- If a data source turns out to need heavy processing (ETL, scraping, ML) rather than a simple API call, revisit: a separate Python service may fit better than cramming that into Next.js API routes.

## Commands

_(none yet — fill in once scaffolded, e.g. `npm run dev`, `npm run build`, `npm test`, `npm run lint`)_

## Workflow

- Branch off `main`: `feature/<name>` or `fix/<name>`.
- Commit, push, open a PR. Don't push directly to `main`.
- Once a build/test/lint pipeline exists, it must pass before merge.

## Team notes for Claude

- This is a **team-shared repo**, not a personal scratch project — confirm before merging PRs, changing shared config (env vars, Vercel project settings), or touching anything other collaborators depend on.
- Keep this file current as the project takes shape. If something here goes stale, fix it in the same PR you noticed it in.
