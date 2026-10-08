# folio. Resume Studio

A polished, responsive Next.js resume maker with an installable PWA experience and a separate finished-resume page for clean PDF output.

## Run locally

```bash
npm install
cp .env.example .env.local
npm run dev
```

Open http://localhost:3000. The builder works without the backend; set `NEXT_PUBLIC_API_URL` to the Express API origin to enable sign-in and registration.

## Build and check

```bash
npm run build
npm run lint
```

## Features

- Logo-first app launch, then a focused resume-building workspace
- 36 designs across Classic, Signature, and Creative collections
- 12 coordinated accent colors and a custom picker that themes the resume and app
- Regular, Large, and Extra-large resume type sizes
- Drafts stay in browser storage
- **View finished resume** opens a separate document page; **Download PDF** opens that page and starts print/save-to-PDF for the built resume only
- Installable phone/desktop PWA with app icons and a service-worker shell

On Android/Chrome use **Install app**; on iPhone/Safari use **Share → Add to Home Screen**.
