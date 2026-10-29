# AGENTS.md

This file provides guidance to AI coding agents working with this repository.

## Commands

- Install dependencies: `npm install`
- Run development server: `npm run dev`
- Run tests: `npm test`
- Run linting: `npm run lint`

## Architecture

- React frontend in `src/`
- API clients in `src/api`
- State management in `src/store`
- Components should be presentational when possible

## Conventions

- TypeScript strict mode enabled
- Prefer functional components
- Use named exports
- Follow ESLint rules

## Never Touch

- `src/generated/*`
- Migration files
- Environment secrets
- CI/CD configuration
- .env files, .github/workflows/, package-lock.json (never edit by hand).
- vite.config.ts and tsconfig files unless I ask.

## Rules for the AI

1. Plan first: describe the plan and wait for my approval before editing files.
2. One task per change, under about 200 changed lines.
3. Never add a dependency, or use --force or --legacy-peer-deps, without asking.
4. Run lint and build before saying a task is done, and show me the output.
5. If something is unclear, ask instead of guessing.
