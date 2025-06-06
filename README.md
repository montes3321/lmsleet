# LMSleet Project Skeleton

This repository contains a basic project structure for building a browser-based video
call application with optional screen drawing or remote control features. The
skeleton consists of a server and a client application.

## Server (`server`)

- Node.js/Express server that serves static files and provides a WebSocket
  signaling channel for WebRTC connections.
- Placeholder module for future remote control implementation.
- Start the server with `npm start` from the `server` directory.

## Client (`client`)

- Minimal React setup bundled with Webpack.
- Entry point in `src/index.js` renders `App` component.
- `public/index.html` loads the bundled script.
- Start the development server with `npm start` from the `client` directory
  after installing dependencies.

This is only a starting point; additional configuration and functionality will
be needed to implement full video calling and remote desktop features.
