# Mareo website

The public site for Mareo, an iPhone app by Zerebro LLC: the landing page, privacy policy, and support page, in English and Spanish. It's served by GitHub Pages from the `main` branch at https://mareo.zereb.ro (the `CNAME` file sets the domain; DNS is a CNAME record `mareo` → `frandemona.github.io` in Cloudflare, DNS only).

| Page | English | Spanish |
| --- | --- | --- |
| Home | `/` | `/es/` |
| Privacy policy (App Store privacy URL) | `/privacy/` | `/es/privacy/` |
| Support (App Store support URL) | `/support/` | `/es/support/` |

It's plain HTML and CSS: no build step, cookies, analytics, or third-party requests. All links are relative, so the site works on the custom domain and at `https://frandemona.github.io/mareo-site/`, which redirects to it.

Both home pages show Apple's official App Store badge (`assets/app-store-badge-{en,es}.svg`, self-hosted, from Apple's Marketing Tools). It links to `https://apps.apple.com/app/id6824806565`, which opens each visitor's own country store. If the privacy policy changes, update its "Last updated" date in both languages.
