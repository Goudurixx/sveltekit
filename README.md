# SvelteKit demo template

**The official SvelteKit demo app, a template to start from: a welcome page, a counter, and "Sverdle", a server-backed Wordle clone.**

> This repository is a **template / demo app**, not an original project. It is the SvelteKit demo published by the SvelteKit team and hosted on Vercel. It pins SvelteKit 1.x, Svelte 3 and the Vercel adapter.

## What is in it

- `/`: a home page with a spring-animated counter component.
- `/about`: a short static page.
- `/sverdle`: a Wordle clone. Game state lives in a cookie, guesses are checked on the server, and the word list is server-only. Includes a `/sverdle/how-to-play` page. Confetti on a win (`@neoconfetti/svelte`).
- Unit tests for the game logic (`src/routes/sverdle/game.test.js`, Vitest) and one Playwright end-to-end check (`tests/test.js`).

## Tech stack

SvelteKit 1 · Svelte 3 · Vite 4 · `@sveltejs/adapter-vercel` · Vitest · Playwright · ESLint and Prettier · pnpm

## Deploy Your Own

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fvercel%2Fvercel%2Ftree%2Fmain%2Fexamples%2Fsveltekit-1&project-name=sveltekit-vercel&repository-name=sveltekit-vercel&demo-title=SvelteKit%20%2B%20Vercel&demo-url=https%3A%2F%2Fsveltekit-template.vercel.app%2F)

_Live Example: https://sveltekit-template.vercel.app_

## Getting started

### Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

### Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

## Speed Insights

Once deployed on Vercel, you can benefit from [Speed Insights](https://vercel.com/docs/concepts/speed-insights) simply by navigating to Vercel's dashboard, clicking on the 'Speed Insights' tab, and enabling the product.

You will get data once your application will be re-deployed and will receive visitors.
