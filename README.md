# DEX.DO — AI token marketplace (landing)

Static landing page — a single `index.html`. EN/RU toggle, early-access form,
Dark Order brand aesthetic. No build step required.

## Deploy on Vercel via Git
1. Push this folder to a new GitHub repo (commands below).
2. Vercel → Add New… → Project → Import this repo → Deploy.
3. It auto-redeploys on every `git push`.

## Configure the lead form
Edit the top of the `<script>` block in `index.html`:
- `CONTACT_EMAIL` — your inbox (used as a mailto fallback).
- `FORM_ENDPOINT` — optional: a Formspree / Tally / your-own POST URL to collect
  submissions automatically. Leave empty to use the mailto fallback.

## TODO before outreach
- Replace the Season button URL (currently a 401-protected preview) with a public one.
- Swap fonts/colors for the exact dex.do brand tokens if needed.

## Local preview
Open `index.html` in a browser, or run: `npx serve .`
