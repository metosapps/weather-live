# Weather Live public site and remote settings

The landing site and legal pages are published at https://metosapps.github.io/weather-live/.

`config/ads-release.json` is fetched by the separate Android package `com.metosapps.weatherlive`. The app accepts only the compiled Google demo/test ad units and `mode: test`; a remote edit cannot substitute real ad units. Increase `revision` with each settings change. To pause ads, set `ads.enabled` to `false`. The app fails closed if settings are missing or invalid.

The Galaxy Store destination is reserved for a future listing. This website can be live before the app is available for download. Samsung IAP product IDs must be created for the new package and verified separately before selling Premium. This repository contains no APK, signing key, or reverse-engineered application code.
