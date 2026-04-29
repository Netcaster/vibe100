# VIBE100

VIBE100 is a Vite + React + Tailwind microsite for VIBE Enterprises.

## Local Preview
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```

## Deploy to Cloudflare Pages with Wrangler
```bash
npm install
npx wrangler login
npm run deploy
```

Access code for the Deal Room preview:

```text
VIBE100
```

## GitHub Setup
```bash
git init
git add .
git commit -m "Initial VIBE100 microsite"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/VIBE100.git
git push -u origin main
```

Then in Cloudflare Pages:
1. Workers & Pages → Create application → Pages → Connect to Git
2. Select repository: VIBE100
3. Framework preset: Vite
4. Build command: npm run build
5. Build output directory: dist
6. Deploy
