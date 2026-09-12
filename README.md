# Pocket Grove public app configuration

This repository hosts public, non-secret remote configuration used by Anniversary Tracker and related Pocket Grove apps.

It must never contain API keys, signing material, user data, private endpoints, or other credentials. Disabled or placeholder entries are not evidence that a feature or app is currently available.

For current Anniversary Tracker information:

- [See screenshots and current features](https://pocketgrove.com/anniversary-tracker/?utm_source=github&utm_medium=referral&utm_campaign=anniversary_config_repo)
- [Download on the App Store](https://apps.apple.com/gb/app/anniversary-tracker/id1570714816?pt=19678800&ct=pg_gh_ann_config&mt=8)
- [Get support](https://pocketgrove.com/support/)
- [Read the privacy policy](https://www.cong-le.com/privacy.html)

## Anniversary Settings promotions

Edit `crossPromotions` in `remote-config.json` to control the Settings-only “More Apps” section:

- Set `enabled` to `false` to hide one app.
- Use `priority` to reorder rows; higher numbers appear first.
- Set `locales` to `[]` for every locale, or list language/locale codes such as `ja`.
- Set `crossPromotions` to `[]` to hide the whole section.

Keep Apple IDs and campaign tokens unique. Use only public App Store products and HTTPS icon URLs.
Existing Anniversary Tracker installations refresh this file at most every four hours.
