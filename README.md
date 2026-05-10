# Dilmani Kiriella - Portfolio Website

A handcrafted, deployment-ready portfolio website and PDF submission package for Dilmani Kiriella.

## Tech / Structure

This package is ready for Vercel deployment. The primary implementation is a single-page Vite-compatible React-style static portfolio with handcrafted HTML/CSS assets.

## Run locally

```bash
npm install
npm run dev
```

If you want a zero-build preview, open `index.html` directly in a browser.

## Deploy to Vercel

1. Push this folder to a GitHub repository.
2. Go to Vercel and import the repository.
3. Keep the default Vite build settings.
4. Deploy.
5. Replace `https://your-vercel-link.vercel.app` inside `index.html` with your actual Vercel URL.
6. Re-export the PDF after replacing the link.

## PDF export

A submission-ready PDF is included separately. To re-export after updating the Vercel URL:

```bash
chromium --headless --no-sandbox --disable-gpu --print-to-pdf=portfolio.pdf index.html
```

Use Chrome/Edge print settings:
- Destination: Save as PDF
- Paper: A4
- Background graphics: ON
- Margins: Default or none

