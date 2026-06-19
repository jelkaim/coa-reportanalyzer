# COA Report Analyzer

A Next.js app for reviewing hemp certificate of analysis reports through a simple mock authentication flow and dashboard experience.

## Local Run

```bash
npm install
npm run dev
```

Open `http://localhost:3000`.

## Build

```bash
npm run build
```

## Current App Flow

- `/login`: mock sign-in screen
- `/signup`: mock account creation screen
- `/verify`: mock verification step
- `/dashboard`: upload and analysis landing page
- `/dashboard/history`: report history view
- `/dashboard/analysis/[id]`: individual analysis details

## Notes

- Authentication is currently local mock state stored in `localStorage`.
- The app is built with Next.js App Router.
- `next.config.ts` pins the Turbopack root to this repository so local runs do not pick the wrong workspace root when multiple lockfiles exist on the machine.

## Latest Update

- Added the latest dashboard layout and navigation shell
- Added report history page
- Kept the project runnable locally on `localhost:3000`
