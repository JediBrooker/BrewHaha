# BrewHaha public pages

Public website for the BrewHaha homebrewing app. Hosted with GitHub Pages from `main`, repository root, on the custom domain `brewhaha.me` (see `CNAME`). DNS is managed in Cloudflare; keep the GitHub Pages records DNS only (not proxied) so GitHub can issue the HTTPS certificate. The old `jedibrooker.github.io/BrewHaha/` addresses redirect to the custom domain.

Three pages, all static HTML sharing `assets/site.css`:

- Home (landing page): https://brewhaha.me/ — `index.html`. Store links, what the app does, with web-sized screenshots in `assets/screens/` (540 px wide, made with `sips` from the App Store marketing captures) and a JSON-LD `MobileApplication` block.
- Support: https://brewhaha.me/support/ — `support/index.html`, Markdown source `support.md`.
- Privacy: https://brewhaha.me/privacy/ — `privacy/index.html`, Markdown source `privacy-policy.md`.

This repository contains the public website and policy source. The iOS and Android application sources are maintained separately. No trackers, analytics, remote fonts, JavaScript frameworks or build dependencies are used. Support email: support@brewhaha.me (Cloudflare Email Routing forwards it to the developer).

Edit the HTML and push to `main` to update the live pages. Keep the corresponding Markdown help/policy source in sync with the support and privacy pages. The store buttons on the home page are built in HTML/CSS; the official App Store and Google Play badge artwork can be dropped in later.
