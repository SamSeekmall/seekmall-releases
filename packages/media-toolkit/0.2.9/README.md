# Media Toolkit 0.2.9 — Chrome desktop unpacked package

The ZIP is a real compiled MV3 extension (9 runtime files) with complete component source and MIT license. Extract it; in Chrome desktop open `chrome://extensions`, enable Developer mode, Load unpacked and choose `Media-Toolkit-0.2.9/dist`. This is not a signed Web Store installer and cannot be installed as a mobile-browser extension.

Exact source: SamSeekmall/sm-media-suite-player bcc17440a7875592925bd1c8f8edcb9ee0e9ab31. Package size/SHA256 and inventory are in PACKAGE.json and the .sha256 file. Manifest ID/key and downloads/storage/loopback permission remain unchanged. Node/TypeScript are not needed to load the bundled extension. Companion functions require the separately installed and running local service; no browser code starts or installs that service.

TypeScript 5.9.2 and 15 component tests passed; ZIP and every packed byte verified. Actual sideload in this execution environment was blocked with ERR_BLOCKED_BY_CLIENT, so no claim of completed real Chrome installation, live pairing or torrent/media transfer. No private user media/accounts/credentials included; no real torrent was used. Newer unaccepted Toolkit review changes are preserved separately and are not mixed in.

Companion full Windows runtime package is not supplied here yet: its FFmpeg/ffprobe vendor and corresponding source/license materials are missing. No partial package is advertised as a full installer. Player's own GPL and third-party obligations remain independent of this component MIT grant.
