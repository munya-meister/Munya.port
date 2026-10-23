# Munyaradzi Mbewe — Frontend Portfolio

Frontend-only React + Vite website. No database, login, Supabase, Express, or Netlify Functions.

## Run locally

```bash
npm install
npm run dev
```

## Deploy

Import `munya-meister/Munya.port` in Netlify or Vercel. Build command: `npm run build`; publish directory: `dist`. No environment variables are required.

## Customize

- Edit `src/data.js` for projects, achievements, links and contact details.
- Place your real portrait at `public/images/portrait.jpg`.
- Place project thumbnails in `public/images/` matching filenames in `src/data.js`. Missing images show a text fallback rather than a broken-image icon.
- Place your real CV at `public/Munyaradzi-CV.pdf` before enabling the CV download button.
- Contact buttons open WhatsApp or the user's email app directly; there is no contact form backend.

No performance statistics or project outcomes are claimed without evidence.
