# Lean Coin Site (Vite + React + Tailwind)

## Quickstart
1) Unzip this project.
2) In the folder, run:

```bash
npm install
npm run dev
```

Open the printed localhost URL.

## Configure
Edit `src/App.jsx` and replace these placeholders at the top:
- `MINT`
- `PUMPFUN_LINK`
- `PUMPSWAP_LINK`
- `TELEGRAM`
- `TWITTER`

Place your logo/banner in `/public` if you swap them out: `lean-logo.png`, `lean-banner.png`.

## Build
```bash
npm run build
```
Output will be in `dist/`.

## Deploy
- **Vercel**: `vercel` from this folder (framework: Vite). Or connect the repo in the Vercel dashboard.
- **Netlify**: set build command `npm run build` and publish directory `dist`.
- **GitHub Pages**: `npm run build` then push `dist` with a static hosting action.
