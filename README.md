# Weather Live public site and remote settings

The landing site, six promotional screenshots, and legal/support pages are published at https://metosapps.github.io/weather-live/.

`config/ads-release.json` is fetched by the separate Android package `com.metosapps.weatherlive`. The release app accepts only its compiled production ad units and `mode: production`; a remote edit cannot substitute different units. Revision 4 has the global and all four placement switches off. Keep them off until the app is live and the owner explicitly authorizes activation; then increase `revision` with each settings change. The app fails closed if settings are missing or invalid.

The Galaxy Store badge points to the reserved package URL. It returns an unavailable page until Samsung publishes the new listing; the website is already live. The six images in `docs/assets/screenshots/` are marketing mockups based on actual app screens, not literal screenshots. Samsung IAP product IDs must be created for the new package and verified separately before selling Premium. This repository contains no APK, signing key, or reverse-engineered application code.
