# Hackathon project

## Goal
Ship a working, demo-able AI app in ~12 hours. Read TASK.md first for the challenge.

## Rules
- Working demo beats perfect code. Build the core flow end to end first, polish later.
- Keep it simple: no new frameworks, no premature abstractions, no extra features not in TASK.md.
- Commit small and often. Run the build before saying something is done.
- Never commit .env or API keys. Use .env.example for placeholders.
- Use Context7 for library docs before writing code against an API.
- After UI changes, check the app with Playwright if it's running.

## Stack
- Frontend: Next.js + Tailwind + shadcn/ui
- Backend: Next.js API routes
- LLM: OpenAI-compatible client, base URL and key from env
- DB: SQLite (swap to Supabase only if needed)

## Commands
- dev: `npm run dev`
- build: `npm run build`
- deploy: see .opencode/skills/deploy

## Definition of done
Deployed URL works, README explains the problem + demo steps, repo pushed.
