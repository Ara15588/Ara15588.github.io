# Ara15588.github.io

GitHub user site, published at https://ara15588.github.io/.

It exists to serve `app-ads.txt` at the root of the domain, where AdMob and the other ad networks look for it. Google Play's developer website for Tray Master is on this domain, and ad networks only read `app-ads.txt` from the domain root, so it can't live in the `traymaster-pages` repository (served under `/traymaster-pages/`).

The game's public pages (privacy policy, account deletion, pre-registration terms) stay in `traymaster-pages`.

## Updating app-ads.txt

Edit `app-ads.txt`, push to `main`, wait for GitHub Pages to publish, check https://ara15588.github.io/app-ads.txt, then use **Check for updates** in AdMob (Apps > App settings > app-ads.txt).
