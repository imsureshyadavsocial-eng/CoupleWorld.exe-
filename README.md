# CoupleWorld Pro 💗

A responsive mini-world for couples, partners, and friends. Includes playful relationship actions, funny generators, mini-games, a love calculator, and shareable message cards.

## Features
- Responsive pastel/neon design for phones, tablets, and desktops
- Kiss, hug, miss-you, cute-fight, and patch-up interactions
- Random flirting lines, apologies, funny excuses, and compliments
- Entertainment-only compatibility calculator
- Truth-or-dare, emoji challenge, and couple prompts
- Create a message card and share a unique link
- Backend API with basic validation, rate limiting, and security headers
- Health endpoint: `/api/health`

## Run locally
Requires Node.js 18+.

```bash
npm install
npm start
```

Open `http://localhost:3000`.

## Deploy
This is a full-stack Node.js project, so GitHub Pages alone cannot run the backend. Deploy it to a Node.js host such as Render, Railway, or another Node-capable service. Set the start command to `npm start`.

The included demo backend writes cards to `data/cards.json`. That works on a persistent local disk, but some hosting providers use ephemeral filesystems; use a database for durable production storage.

## Project files
- `server.js` — API and web server
- `package.json` — dependencies and start command
- `.env.example` — optional configuration
- `.gitignore` — excludes runtime files
- `public/index.html` — application layout
- `public/styles.css` — responsive styling and animations
- `public/app.js` — interactive features and API calls
- `public/manifest.json` — installable web app metadata
- `public/404.html` — simple fallback page
