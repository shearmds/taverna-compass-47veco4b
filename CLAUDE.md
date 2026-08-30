# taverna-compass

One static page: a restaurant guide for a Greece trip (Athens / Santorini / Paros),
plotting each restaurant against the hotel on that island. Generated 2026-08-30.

- `index.html` is the whole app — self-contained, no build step, no dependencies
  beyond Google Fonts. Edit it directly and push; GitHub Pages redeploys.
- The data lives in the `ISLANDS` object in the inline `<script>`.
- **The repo name carries a random suffix on purpose.** Pages sites are world-readable
  even from a private repo, and this page lists real hotel addresses — the obscure name
  plus `robots.txt` and the `noindex` meta are the only things keeping it unfindable.
  Don't rename it to something guessable.
