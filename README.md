# scarafone.com

Personal portfolio site for **Brent Scarafone**.

This repo is intentionally:
- **Static-deployable** (GitHub Pages) via Next.js static export
- **PR-first** (feature branches → protected `main`)
- **A showcase of craft** (clear structure, accessible UI primitives)

## What this site is

A portfolio + writing hub. It should link to Codeductor, projects, and contact.

## Tech

- Next.js (App Router) + TypeScript
- CSS (no Tailwind)
- Radix UI primitives (accessibility-first building blocks)

## Local development

```bash
npm ci
npm run dev
```

## Build (static export)

```bash
npm run build
```

Output is generated to `out/`.

## Release / deploy

This project is intended to deploy from **tags/releases** (not every push).
