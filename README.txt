Mnet Video Saver — Android PWA prototype

Files:
- index.html: mobile interface, URL validation and post ID extraction
- manifest.webmanifest: installable PWA metadata
- sw.js: basic app-shell cache

Important:
This is a front-end prototype only. It does not access Mnet Plus cookies, authenticated media streams, or extract/reconstruct DASH video. To install as a PWA, host these files on an HTTPS origin, then open that URL in Android Chrome and choose ⋮ > Install app / Add to Home screen.

The current sandbox HTML preview can be opened locally for a quick UI check, but PWA installation and service worker require HTTPS (or localhost).
