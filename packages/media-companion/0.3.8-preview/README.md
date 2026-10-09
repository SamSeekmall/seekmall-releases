# Latest one-click Windows portable preview

Source checkpoint: `46744ab958d41c1f5da382d65b20474158a1f777`. See `ONE-CLICK-DELIVERY-46744ab958d4.json` for exact runtime/source ZIP hashes. These are additional real archives; the previous release below remains available unchanged.

Download `media-companion-0.3.8-windows-x64-preview-46744ab958d4.zip`, fully extract, and double-click **start-companion.cmd**. Keep the console window open for service and pairing messages. **stop-companion.cmd** stops only the owned service; **companion-status.cmd** reports status. Uses bundled Node without npm install, administrator rights, autostart or registry changes. Pair once in an official desktop Chrome Toolkit or Player extension. Webpage playback remains independent; the web domain is not added to the fixed extension Origin allowlist.

Matching public source: `media-companion-0.3.8-corresponding-source-46744ab958d4.zip` includes all 44 component files, packaging recipes and the same eight vendor source archives plus 176 original npm tarballs. Own code remains AGPL-3.0-only; FFmpeg remains GPL-3.0-or-later. Native Windows, GPU and actual extension acceptance are not claimed.

## Historical delivery (unchanged)

# Media Companion 0.3.8 — Windows x64 portable preview

Two real ZIP files accompany `DELIVERY.json`: the runtime and its complete matching source/recipe/notice set. The exact component source checkpoint is `9f8fcbfabe5ec6e560cbcea4a89bc38a69780051`. Runtime: official Node 24.19.0; fixed-source FFmpeg/ffprobe 9.0.2; 176 original lockfile-installed packages with the existing three safety patches. No user data or credentials are included.

Extract the runtime to a short local directory. It is a portable payload for the existing local service manager, with no automatic installation/start/registration. From its extracted root use:

```text
runtime\node.exe scripts\lifecycle.mjs status
runtime\node.exe scripts\lifecycle.mjs start
runtime\node.exe scripts\lifecycle.mjs stop
```

The service remains at `127.0.0.1:32145` and accepts only the two existing fixed official Chrome extension Origins. It remains optional for webpage playback. Public torrent/P2P, arbitrary paths or arguments are not enabled by this package.

Own code: AGPL-3.0-only. FFmpeg: GPL-3.0-or-later, with GPL-2.0-or-later x264 under compatible terms. Full Node/codec/header/npm/toolchain-runtime notices and matching sources/recipes are supplied. The source ZIP includes all eight source archives and all 176 verified original npm tarballs; it is a public source delivery, not a private-repository source link. Retain these materials when redistributing; this is not a closed-source media chain.

Passed: package/hash/source/PE64/notice checks, nine packaging gate cases, Linux launcher/lifecycle, and five actual software conversion modes with SRT/ASS text and timing (Linux Node + actual Windows FFmpeg via Wine). Real Windows, GPU, signed installer and real extension integration are not accepted. Wine 8 cannot initialize the Windows Node script crypto runtime; the official binary is unchanged and its security checks were not disabled. The new FFmpeg/ZIP are unsigned; do not disable OS protections. This preview does not accept the Player website's existing HTTP429/full-source-SHA publication gate.
