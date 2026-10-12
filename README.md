# Test-Project

Node.js workspace with a **TypeScript** + **Next.js** (App Router) app.

## Tech stack

| Layer | Choice |
| --- | --- |
| Runtime | Node.js |
| Language | TypeScript |
| Framework | Next.js 16 (App Router) |
| UI | React 19 |
| Styling | Tailwind CSS 4 |
| Lint | ESLint |

## Project layout

```
Test-Project/
├── ai/cursor.md          # AI / project notes
├── package.json          # workspace root (dotenv)
└── test-project/         # Next.js + TypeScript app
    ├── src/app/          # App Router pages
    ├── next.config.ts
    └── tsconfig.json
```

## Requirements

- Node.js 20 or later
- npm (comes with Node)

## Getting started

Install and run the Next.js app:

```bash
cd test-project
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

Edit `test-project/src/app/page.tsx` — the page reloads as you save.

## Scripts (`test-project`)

| Command | What it does |
| --- | --- |
| `npm run dev` | Start the local dev server |
| `npm run build` | Production build |
| `npm start` | Serve the production build |
| `npm run lint` | Run ESLint |

## License

ISC
