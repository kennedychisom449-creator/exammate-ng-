ExamMate NG PWA prototype
========================

Files:
- index.html: app
- manifest.webmanifest: install metadata
- sw.js: service worker for app-shell caching
- icon-192.png and icon-512.png: app icons

Important:
1. A service worker and install prompt require HTTPS hosting (or localhost for testing). Opening index.html as file:// will run the quiz but will not install/offline-cache as a PWA.
2. This package is a prototype. It contains original sample questions, not official JAMB past questions.
3. Progress is saved in localStorage on the same browser/device. It is not synced across devices.
4. For real launch, review question content rights/accuracy, privacy, security, and payments.

Free beginner hosting options to investigate: GitHub Pages (static HTTPS hosting) or Netlify. Create a repository/site, upload these files preserving the root structure, enable HTTPS, then open the hosted URL in Chrome Android. Use Chrome menu > Install app / Add to Home screen when available.
