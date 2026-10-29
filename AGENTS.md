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

## Rules for the AI

- Always run lint before proposing changes
- Prefer updating existing files over creating new ones
- Do not introduce new dependencies without justification
- Preserve public APIs unless explicitly asked
