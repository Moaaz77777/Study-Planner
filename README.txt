# My Study Planner — installable PWA

This folder contains your study planner as an installable web app.

## Important
A Progressive Web App must be hosted on an HTTPS website (or localhost) before the browser can install it. Opening `index.html` directly from your phone's Downloads folder will not enable installation or offline app behavior.

## Easiest route
1. Keep all files and folders together; do not rename or remove anything.
2. Upload the contents of this folder to a static website host that provides HTTPS (for example, Netlify Drop).
3. Open the resulting HTTPS link in Chrome on your Android phone.
4. Open Chrome's menu (⋮) and choose **Install app** or **Add to Home screen**.
5. Confirm. The Study Planner icon will appear on your home screen.

## Your data
Tasks and notes remain saved in that browser on that device. This version has no account or cloud sync. The service worker caches the app so it can open offline after the first successful visit.

## Updating later
If you change the app files, upload the updated folder again. The service worker cache version can be increased in `service-worker.js` if needed.
