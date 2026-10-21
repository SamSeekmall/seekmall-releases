# SM Clean View (SM 净览) 0.4.7 — Chrome unpacked trial package

Content blocker based on uBO Lite (MV3, declarative filtering) with SM controls, bilingual UI and brand. Chrome / Edge 122+ on desktop.

## Install

1. Extract the ZIP to a permanent folder (the browser keeps reading it).
2. Open `chrome://extensions`, turn on Developer mode, choose **Load unpacked** and select the extracted folder (the one that contains `manifest.json`).
3. After replacing files with a newer version, click **Reload** on the extension page. Export your configuration from the control centre before upgrading.

## Status — read before relying on it

- Local-trial build (`channel: local-trial`): not a store release, not signed, no automatic update.
- Passed the project's unit tests (33), verification, a reproducible build and the Chromium browser suite recorded in the 0.4.7 notes. It did **not** pass the project's release-script gate (Edge browser tests and popup performance gates were not re-run) and has not been loaded in a real stable Chrome. See `RELEASE-SM.md` inside the ZIP.
- Mobile builds (Firefox/Android, Safari/iOS) are experimental sources only and are not included.

## License and source

GPL-3.0-or-later; full text is `LICENSE.txt` inside the ZIP. Matching source for this exact build: `sm-clean-view-0.4.7-corresponding-source-d632c6f.zip` (commit d632c6f). Build: Node 24, `npm ci --prefix sm/build-tools`, `node sm/build.mjs`. Upstream filter lists and uBO Lite keep their own notices inside the package.

## Integrity

SHA-256 values are in `PACKAGE.json` and the `.sha256` files next to each ZIP. No credentials or private user data are included.
