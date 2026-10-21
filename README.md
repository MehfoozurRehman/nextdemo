# nextdemo

A Next.js 13 Pages Router project created from the default starter, with the starter page and sample API route still in place.

**Status:** Stub. `pages/index.js` still has the create-next-app title and markup, and the repository has fewer than five real source files.

## The problem

No product problem is described. The project is the stock starter that `create-next-app` generates, kept as a base for prototypes.

## What it does

- Renders the default starter home page in `pages/index.js`, with Inter loaded through `next/font` and CSS module styles from `styles/Home.module.css`.
- Serves the sample API route at `pages/api/hello.js`.
- Sets up the global app and document shells (`pages/_app.js`, `pages/_document.js`).

## How it's built

- Next.js 13 Pages Router with React 18, in JavaScript.
- Styling with `styles/globals.css` and CSS modules.
- The font import uses the `@next/font/google` package, which is the older name for `next/font`.

## Running it locally

From `package.json`:

```bash
npm install
npm run dev      # next dev
npm run build    # next build
npm run start    # next start
npm run lint     # next lint
```

## What's left

- The page title and content are still the create-next-app defaults.
- The sample API route and starter markup should be replaced or removed before this is used for a real project.
- Next.js 13 is an older release.
- No tests.
