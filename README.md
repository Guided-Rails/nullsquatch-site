# nullsquatch-site

Static placeholder for https://nullsquatch.com, served by GitHub Pages from
`main` at the repo root. Plain HTML styled with Tailwind from the CDN to match
guidedrails.com: no build step, no analytics. The only JavaScript is the
Tailwind CDN script and its inline config (the `brand` color).

- `index.html`: the landing page.
- `privacy.html`: the privacy policy stub, served at `/privacy`.
- `CNAME`: the custom domain for GitHub Pages.

This site is throwaway. It exists to claim the domain and to give App Store
Connect a privacy policy URL before TestFlight. The real marketing site
belongs in the Rails app at `Guided-Rails/nullsquatch`.

## Teardown

When the first Rails-rendered marketing page ships:

1. Point DNS at the Rails host.
2. Remove the custom domain from this repo's Pages settings.
3. Archive this repo.
