# Vite React TypeScript Template

A starter template for [bolt.diy](https://github.com/stackblitz-labs/bolt.diy).

## Purpose

This template is designed for use with **<https://github.com/stackblitz-labs/bolt.diy>**. bolt.diy fetches
these files at runtime and imports them into a fresh WebContainer project when you ask for a Vite + React +
TypeScript project, so everything here needs to install and build with no extra setup.

Modified by [Dustin Loring](https://github.com/Dustinwloring1988) (Dustinwloring1988) in October 2026.

## Stack

| Package | Version |
| --- | --- |
| Vite | ^8.3.4 |
| React | ^19.3.0 |
| React-DOM | ^19.3.0 |
| TypeScript | ~6.0.3 |
| @vitejs/plugin-react | ^6.1.2 |
| Tailwind CSS | ^3.4.1 |

Node 20 or newer is required.

## Commands

```bash
npm install   # install dependencies
npm run dev   # vite — dev server
npm run build # vite build — production build
npm run preview # vite preview — local preview server
```

## About this template

A Vite + React + TypeScript project with `src/main.tsx` as the entry point. `lucide-react` provides
the icon set. Tailwind CSS is configured but minimal. ESLint and TypeScript are configured for strict
checking.

## Upgraded to Vite 8, React 19, TypeScript 6.0.3 (October 2026)

Moved from Vite 5, React 18, and TypeScript ~5.5. Each step was verified with `npm install` and
`npm run build`:
- Vite: 5 → 6 → 7 → 8
- @vitejs/plugin-react: 4 → 6 (Vite 8 compatibility)
- React: 18 → 19
- TypeScript: ~5.5.0 → ~6.0.3 (ecosystem standard; @remix-run/dev and Angular cap TS at <7)

Build passes with `npm run build`. The dev server (`npm run dev`) and preview (`npm run preview`)
also work.

TypeScript is on 6.x rather than 7: the broader ecosystem caps TS at `>=6.0 <7.1` for compatibility
with `@remix-run/dev`, `svelte-check`, and `@angular/compiler-cli`.

## Verification

- `npm install` and `npm run build` pass
- Confirmed the dev server starts with HMR and the app renders correctly
- `npm run preview` serves the production build locally