# sallyskoufis-warrior-soul — SALLY SKOUFIS™ Warrior Soul buyer link

A static, no-build site: the Warrior Soul film experience plus the buyer room.

## Deploy on Vercel
1. Import this repo in Vercel → Framework preset: **Other** → no build command, output directory `/`.
2. Name the project `sallyskoufis-warrior-soul` so the link reads sallyskoufis-warrior-soul.vercel.app. Deploy; that URL is the link Jordi sends through Mirakl Connect.

## Files
- `index.html` — Part 1: explorable worlds (Australian icon, runway, culture, bestsellers, handmade, conscious, America, Warrior Soul); Part 2: partner room for marketplaces
- `film.mp4` — Warrior Soul film, 50s, web-compressed (6 MB, no audio)
- `poster.jpg`, `still_38.jpg` — stills from the film
- `vercel.json` — caching; `noindex` so the link stays out of search results

## Editing
In `index.html`, near the top of the `<script>`:
- `CONTACT` — name, title, email for the Contact tab and "Request line sheet" button
- `WORLDS` — each world's copy, background tone and floating images
- Buyer room terms marked `to confirm` live in the "Working with us" pane.

Product images load from the Shopify CDN.
