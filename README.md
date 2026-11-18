# ID Appointment V5

React/Vite frontend connected to Supabase.

## Run locally
1. Install Node.js 20 or newer.
2. Open a terminal in this folder.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open the local URL shown by Vite, usually http://localhost:5173.

## Supabase
The included `.env` contains the project URL and publishable browser key supplied for this prototype. Never place a Supabase secret/service-role key in frontend code.

## Build
Run `npm run build`. Output is placed in `dist/`.

## Azure Static Web Apps later
Deploy this repository as a Vite app. Configure environment variables `VITE_SUPABASE_URL` and `VITE_SUPABASE_PUBLISHABLE_KEY` in the hosting environment for the production build.
