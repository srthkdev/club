# AI Chat Local

A privacy-first, local-first AI chat interface and development hub. Built with Next.js, shadcn/ui, Drizzle ORM, TanStack, and Bun. Supports local LLMs (Ollama, LM Studio, etc.), external APIs, and advanced analytics—all in a clean web UI.

## Features
- Chat with local and API models (Ollama, LM Studio, OpenAI, etc.)
- Full privacy: all data stored locally (SQLite)
- Performance dashboard: tokens, latency, cost, resource usage
- Integrated terminal for model management and shell access
- Model marketplace and management
- Advanced analytics and system monitoring
- Modern UI with shadcn/ui and Tailwind CSS

## Tech Stack
- Next.js (App Router, TypeScript)
- Bun (package manager)
- shadcn/ui (UI components)
- Drizzle ORM + SQLite (local DB)
- TanStack (React Query, Table, Virtual)
- Zustand (state management)
- xterm.js (terminal)
- Vercel AI SDK (API integration)

## Getting Started
```sh
bun install
bun dev
```

## Project Structure
- `src/` — App, components, lib, hooks, stores
- `drizzle.config.ts` — Drizzle ORM config
- `README.md` — Project overview
- `project.md` — Detailed plan and features

## License
MIT
