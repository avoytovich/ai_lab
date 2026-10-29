# Copilot instructions for ai_lab

The instructions in this file apply to any AI coding agent working with this repository, including Claude Code, Gemini, Copilot, and similar tools.

## Commands

- Install: npm install
- Dev server: npm run dev
- Build: npm run build
- Lint: npm run lint
- Tests: [none yet, added in Phase 2]

## Architecture

- React + TypeScript app created with Vite; all code lives in src/.
- [Where components live]
- [How state or data fetching is handled]

## Conventions

- TypeScript strict mode; function components with hooks.
- [Naming and file structure you want]

## Never touch

- .env files, .github/workflows/, package-lock.json (never edit by hand).
- vite.config.ts and tsconfig files unless I ask.

## Rules for the AI

1. Plan first: describe the plan and wait for my approval before editing files.
2. One task per change, under about 200 changed lines.
3. Never add a dependency, or use --force or --legacy-peer-deps, without asking.
4. Run lint and build before saying a task is done, and show me the output.
5. If something is unclear, ask instead of guessing.
