# dannyboi's Karaoke — GitHub Pages HTTPS test

This repository contains a standalone HTTPS browser player to test YouTube iframe error 153 on LG webOS.

## Enable GitHub Pages
Repository Settings > Pages > Deploy from a branch > main > /(root).

Expected URL: https://danieldizon620-stack.github.io/dannyboi-karaoke/

## Important limitations
- This is a **test web player**, not a packaged LG webOS .ipk update.
- YouTube Error 153 may still occur; HTTPS does not guarantee that the TV's browser sends all client identity headers.
- PeerJS uses a public signaling service. Older LG webOS browsers may not support the CDN bundle or WebRTC; TV ID may remain unavailable.
- Remote pairing message compatibility is provisional; verify against the installed Android remote.
- Search uses a user-entered YouTube Data API key stored in the browser; do not commit API keys to a public repository.
