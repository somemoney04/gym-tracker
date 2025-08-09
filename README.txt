Gym & Nutrition Tracker (PWA)
=============================

This folder contains a ready-to-host Progressive Web App that works offline and supports iOS "Add to Home Screen".

Files:
- index.html
- sw.js
- manifest.webmanifest
- icon-192.png
- icon-512.png

How to publish from iPhone (Safari):
1) Go to https://github.com (sign in). Create a new repo (Public is fine).
2) Tap "Add file" → "Upload files" → upload all 5 files.
3) Go to repo Settings → Pages → set "Branch: main / root" → Save.
4) Open the GitHub Pages URL shown (https://<yourname>.github.io/<repo>/).
5) In Safari, tap Share → Add to Home Screen.

Tip: After updating files, revisit the site and choose "Add to Home Screen" again or just refresh; service worker cache is versioned (2025-08-09T10:47:13.314064Z).

Self-tests: add ?test=1 to the URL and check the console for assertions.
