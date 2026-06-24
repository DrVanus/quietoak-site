# quietoak-site

Marketing + legal site for **Quietoak** (iOS DBT-skills companion app). Static
HTML/CSS — no build step. Adapted from the `storyvault-site` scaffold, re-themed
to the Quietoak calm-daytime palette (sea-teal / sage / sand, Nunito ≈ SF Pro
Rounded). Deploy on GitHub Pages (or any static host) at **quietoak.app**.

## Pages
- `index.html` — landing (hero, how-it-works, the 6 companions, features, crisis-always-free, pricing, FAQ, disclaimer)
- `privacy.html` — privacy policy (on-device-first, AI providers, SB 243 safety log, no HIPAA claim, FTC Health Breach Rule, delete-my-data)
- `terms.html` — terms (self-help not therapy, AI companion disclosure, crisis disclaimer, 18+, Plus billing)
- `support.html` — support + crisis resources
- `404.html`, `robots.txt`, `sitemap.xml`, `.nojekyll`, `legal.css`

## Assets (from ~/Desktop/Anchor-Brand + ~/Desktop/Anchor-Ads)
- `quietoak-icon.png` — app icon (oak), used as favicon + og:image
- `quietoak-wordmark.png` — two-tone wordmark
- `companions/*` — the six companions + `group.png` hero, `scene-welcome.png`

## App ↔ site contract
The iOS app's legal links must resolve here. Point them at
`https://quietoak.app/privacy.html` and `https://quietoak.app/terms.html`
(these exact files exist — avoids the Saffra legal-URL 404 lesson). Email:
hi@quietoak.app.

## Before publishing
- Buy/point the **quietoak.app** domain; set up email forwarding for hi@quietoak.app.
- Replace the indicative Plus prices if they change ($9.99/mo · $59.99/yr from the StoreKit).
- Add real App Store device screenshots once the build is ready (a `screenshots/` section can slot into index.html like storyvault-site).
