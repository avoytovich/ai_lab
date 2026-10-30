# AGENTS.md

This file provides guidance to AI coding agents working with this repository.

## Commands

- Install: `npm install`
- Dev server: `npm run dev`
- Build: `npm run build`
- Lint: `npm run lint`
- Tests: none yet (added in Phase 2)

## Architecture

- React + TypeScript app created with Vite. All code is in `src/`.
- Entry point: `src/main.tsx`, which renders `App` from `src/App.tsx`.
- Styles: plain CSS in `src/index.css` (global) and `src/App.css`.
- Static assets: `src/assets/`.
- Do not create new top-level folders in `src/` (such as `api`, `store` or `components`) without asking. Propose the structure in the plan first.

## Conventions

- TypeScript strict mode enabled
- Prefer functional components with hooks
- Use named exports in new code; leave existing default exports alone
- Follow ESLint rules

## Never Touch

- `.env` files and anything that holds secrets
- `.github/workflows/`
- `package-lock.json` (never edit by hand)
- `vite.config.ts` and tsconfig files unless I ask

## Rules for the AI

1. Plan first: describe the plan and wait for my approval before editing files.
2. One task per change, under about 200 changed lines.
3. Never add a dependency, or use --force or --legacy-peer-deps, without asking.
4. Run lint and build before saying a task is done, and show me the output.
5. If something is unclear, ask instead of guessing.
