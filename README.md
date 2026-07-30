# HT Mobile - releases

Installers only. No source code lives here.

This repository is the auto-update feed for HT Mobile. The app reads only `ht-mobile.yml` from the newest published release.

## Rules

- Every release needs all three files: `ht-mobile.yml`, the installer `.exe`, and the `.exe.blockmap`. A missing `.yml` means the shop never updates, and the release still looks complete.
- Never delete or re-tag a published release.
- To fix a bad release, publish a higher version. Downgrades are refused by the app on purpose.
- This repo must be reachable (public) at the moment the shop's app checks, or the update is silently missed.

See `UPDATES.md` in the source repo for the full process.
