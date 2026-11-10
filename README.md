# Pocket Arabic: privacy policy

The public privacy policy of **Pocket Arabic** (`com.ora.afl`, "Pocket Arabic for Non-Natives" on Google Play), the app that
teaches Arabic to non-native speakers, in English and Arabic, served by GitHub Pages:

**https://aoraoraor.github.io/pocketafl-privacy-policy/**

- `index.html` is the whole site: one self-contained page (no external scripts, fonts, cookies or analytics). English and
  Arabic are on the same page; `?lang=en` or `?lang=ar` picks the language, otherwise the browser language does (English
  unless the browser is Arabic).
- The app opens this URL from Help and privacy → Privacy policy (the `privacy_url` of `projects/afl/project.json` in
  `aoraoraor/app_engine`), adding `?lang=`. Use the same URL in Google Play Console → App content → Privacy policy.

## Hosting

GitHub → this repo → **Settings → Pages** → Source: **Deploy from a branch**, Branch: **main**, folder **/ (root)** → Save.
The site is live a minute later.

## Updating

Edit both languages in `index.html` and change the "Last updated" date in both. Keep the policy in step with the app's
real data practices (the engine's `docs/ANALYTICS.md`, `docs/BACKUP_RESTORE.md`) and with the Play Console Data safety form.

© 2026 Ahmed Orabi. All rights reserved.
