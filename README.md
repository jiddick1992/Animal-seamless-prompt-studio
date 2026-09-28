ANIMAL SEAMLESS STOCK PROMPT STUDIO

Files:
- index.html: app UI
- app.js: JavaScript logic
- data.js: 1,000 records
- manifest.webmanifest: PWA metadata
- sw.js: offline cache

Android:
1. Put the folder on an HTTPS web host.
2. Open index.html in Chrome.
3. Use browser menu -> Add to Home screen / Install app.

iPhone/iPad:
1. Put the folder on an HTTPS web host.
2. Open in Safari.
3. Share -> Add to Home Screen.

Note:
A PWA service worker generally requires HTTPS (localhost is also allowed for development).
Opening index.html directly as a local file still lets the basic interface run, but PWA install/offline caching is not guaranteed.

The app is a production helper, not an upload bypass. Always verify the current marketplace rules and inspect each asset.
