# Ledger

**Ledger** is an offline-first daily logging instrument designed for speed, clarity, and intentional reflection.

No accounts. No AI. No cloud dependency.

## Features

- Local-first storage (no backend)
- Voice input (on-demand, permission-safe)
- Structured daily prompts
- Export (JSON, TXT, Markdown)
- Web Share API support
- Haptic + audio feedback
- Installable PWA
- Offline capable

## Philosophy

Ledger is built as a tool, not a feed.

It prioritizes:
- frictionless input
- tactile interaction
- daily consistency

## Tech Stack

- React (via ESM)
- Tailwind CSS (CDN)
- Service Worker (offline caching)
- localStorage (persistence)

## Install

1. Open the app in a browser
2. Tap "Install"
3. Use like a native app

## Export Format

```json
{
  "date": "YYYY-MM-DD",
  "text": "...",
  "prompts": {},
  "updatedAt": "...",
  "exportedAt": "..."
}
