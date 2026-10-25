# Weather Live public site and remote settings

The landing site and legal pages are published at https://metosapps.github.io/weather-live/.

`config/ads-release.json` is fetched by the separate Android package `com.metosapps.weatherlive`. The release app accepts only its compiled production ad units and `mode: production`; a remote edit cannot substitute different units. Revision 4 has the global and all four placement switches off. Keep them off until the app is live and the owner explicitly authorizes activation; then increase `revision` with each settings change. The app fails closed if settings are missing or invalid.

The Galaxy Store destination is reserved for a future listing. This website can be live before the app is available for download. Samsung IAP product IDs must be created for the new package and verified separately before selling Premium. This repository contains no APK, signing key, or reverse-engineered application code.
