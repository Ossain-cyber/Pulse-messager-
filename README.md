# Pulse Messenger

Pulse is a lightweight, privacy-focused messenger PWA.

## Frontend
- Offline-first local storage with IndexedDB
- PWA service worker
- Encrypted message payloads
- WebRTC peer-to-peer data channels
- Render signaling server for connection setup
- Blue + ash visual system
- Phone-first messenger interface

## Signaling server
The frontend connects to:
`wss://pulse-server-moml.onrender.com`

The signaling server is used to help peers establish WebRTC connections. Message payloads are not stored by the signaling server.

## Deployment
This repository can be hosted as a static site on GitHub Pages or another static host.
