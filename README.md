# FallFeed v - sovereign professional-service workflow tool 2026

> **FallFeed is a browser-run, single-file workflow tool for sovereign professional-service publishing, bringing together Ed25519-signed posts, WebRTC mesh sharing, and offline-first access in version.**

[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/kellytyler1993/fallfeed-webrtc-mesh?style=flat-square)](https://github.com/kellytyler1993/fallfeed-webrtc-mesh)

---

<p align="center">
  <a href="https://kellytyler1993.github.io/fallfeed-webrtc-mesh/">
    <img src="https://img.shields.io/badge/Download-FallFeed%20Latest-brightgreen?style=for-the-badge" alt="Download FallFeed">
  </a>
</p>

> **[Direct Download - FallFeed v](https://kellytyler1993.github.io/fallfeed-webrtc-mesh/)**

---

[Download Latest Build](https://kellytyler1993.github.io/fallfeed-webrtc-mesh/)

---

## What FallFeed Is

FallFeed is a feed-oriented browser application centered on signed publishing and peer-to-peer distribution. It targets users who want a compact, self-contained way to author and share structured updates without pulling in a heavyweight application stack.

Delivered as one HTML file and built to operate as an offline-capable PWA, it fits well in minimal deployments and self-hosted workflows. With IndexedDB for persistence, a service worker for caching, and WebRTC mesh support for sharing, it is suited to local usage, peer following, and portable publishing.

---

## Highlights

- Ed25519-signed posts for authenticated feed entries
- WebRTC mesh publishing for peer-to-peer distribution
- Peer subscriptions for following shared feeds
- Chronological feed layout for straightforward reading
- JSON export for moving or archiving data
- Offline-capable PWA behavior for use without constant connectivity
- Single-file implementation with no framework dependency
- IndexedDB-backed local storage with service worker support

---

## Getting Started

1. Download or clone the repository.
2. Open the single HTML file in a modern web browser.
3. If you are serving it locally, use any static file server and load the page from that address.

Example:

`git clone https://github.com/kellytyler1993/fallfeed-webrtc-mesh.git
`cd fallfeed`

Then open the HTML entry file directly, or start a local server if your browser setup prefers hosted access.

---

## How It Works

Launch FallFeed in the browser, then create or load a feed. From there, you can publish signed posts, connect with peers, and review updates in time order.

Typical workflow:
- Create a post and sign it with Ed25519
- Share or connect through WebRTC mesh links
- Read incoming updates in the feed timeline
- Export data as JSON when you need a portable copy
- Use the app offline once it has been installed or cached

If you are running it as a local file, refresh behavior and browser permissions may vary depending on the browser and storage model.

---

## Data and Settings

FallFeed stores its working data inside the browser. The main local stores are:

- IndexedDB for saved content and state
- Service worker cache for offline availability
- Browser PWA install data for app-like use

If the project exposes app-specific settings in the interface, adjust them there rather than expecting a separate config file. For browser-managed permissions, review your site, storage, and network settings in the browser.

---

## Requirements

- A modern web browser with JavaScript support
- Browser support for IndexedDB
- Service worker support for offline PWA behavior
- WebRTC support for mesh publishing and peer subscriptions
- Enough local browser storage for feed data and exports
- A runtime that can open a single HTML file or a static hosted page

---

## FAQ

**How do I access FallFeed?**  
Open the HTML file in a browser, or use the hosted build from the project download link.

**Does it work offline?**  
Yes, it is designed as an offline-capable PWA once cached or installed.

**Where is the data stored?**  
Local data is kept in browser storage, primarily through IndexedDB.

**Can I move my feed data elsewhere?**  
Yes, JSON export is included for sharing or backup workflows.

**What if WebRTC is not available?**  
Mesh publishing and peer subscriptions depend on browser support, so behavior will vary by browser and environment.

**How are updates handled?**  
Check the repository build or release link for the latest available version.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
