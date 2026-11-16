# hydrotylerking.github.io

Root site for HydroTylerKing's GitHub Pages.

- `/` redirects to the [Hot Springs Map](https://hydrotylerking.github.io/hotsprings/) (repo: HydroTylerKing/hotsprings).
- `/.well-known/assetlinks.json` holds the Digital Asset Links that let the Android app (a Trusted Web Activity) open the map full screen. It must list the app's package name and the SHA-256 fingerprints of both the upload key and Google Play's app signing key.
- `.nojekyll` makes GitHub Pages serve the `.well-known` folder.
