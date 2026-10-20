# Mareo website

The public site for Mareo, an iPhone app by Zerebro LLC: the landing page, privacy policy, and support page, in English and Spanish. It's served by GitHub Pages from the `main` branch.

| Page | English | Spanish |
| --- | --- | --- |
| Home | `/` | `/es/` |
| Privacy policy (App Store privacy URL) | `/privacy/` | `/es/privacy/` |
| Support (App Store support URL) | `/support/` | `/es/support/` |

It's plain HTML and CSS: no build step, cookies, analytics, or third-party requests. All links are relative, so the site works at `https://<user>.github.io/mareo-site/` and on a custom domain.

After the App Store release, replace the "Coming soon" badge on both home pages with Apple's official "Download on the App Store" badge, linked to the app. If the privacy policy changes, update its "Last updated" date in both languages.
