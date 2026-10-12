# test

Node.js app with TypeScript and Next.js.

## Tech stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Framework:** Next.js (App Router)
- **UI:** React + TypeScript
- **Package manager:** npm

## Getting started

```bash
npm install
```

Next.js is not scaffolded yet. After setup, typical scripts will be:

```bash
npm run dev     # local development
npm run build   # production build
npm run start   # run the production server
```

## Project layout (planned)

```
app/          Next.js App Router (pages and API routes)
public/       static assets
```

## Conventions

- TypeScript everywhere — no new `.js` / `.jsx` files
- App Router (`app/`) instead of Pages Router
- Server Components by default; `"use client"` only when needed
- API routes in `app/api/`

## License

ISC
