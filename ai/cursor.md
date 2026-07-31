# Cursor AI Guidelines

This file provides context and instructions for AI assistants working in this project.

## Project Overview

A Node.js web application built with TypeScript and Next.js.

## Tech Stack

| Layer | Technology |
|-------|------------|
| Runtime | Node.js |
| Language | TypeScript |
| Framework | Next.js (App Router) |
| Package manager | npm |

### Conventions

- Use TypeScript strictly — avoid `any` unless unavoidable
- Prefer Next.js App Router patterns (`app/` directory, Server Components, Server Actions where appropriate)
- Use functional React components with hooks
- Colocate related files (components, types, utils) by feature when possible
- Environment variables via `.env.local` — never commit secrets

## Goals

- Keep changes focused and minimal
- Follow existing code conventions and patterns
- Prefer simple, readable solutions over clever abstractions

## Coding Standards

- Match the style of surrounding code
- Add comments only for non-obvious logic
- Avoid unrelated refactors when fixing a specific issue
- Use named exports for components and utilities unless a default export is required by Next.js

## AI Assistant Instructions

When working in this project:

1. Read relevant files before making changes
2. Reuse existing utilities and patterns instead of duplicating logic
3. Run or suggest tests when behavior changes
4. Do not commit unless explicitly asked
5. Follow Next.js and TypeScript best practices for this stack

## File Structure

```
ai/
  cursor.md       # AI guidance (this file)
app/              # Next.js App Router pages and layouts
components/       # Shared React components
lib/              # Utilities, helpers, and shared logic
public/           # Static assets
```

## Notes

<!-- Add project-specific rules, conventions, or context below -->
