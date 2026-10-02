# BRUO

Café-style coffee at home. Static PWA, no build step.

## Put it on GitHub and Vercel
1. Create a new GitHub repo and upload everything in this folder (index.html, sw.js, manifest.webmanifest, vercel.json and the three icons).
2. On vercel.com choose Add New, then Project, import the repo and press Deploy. Leave every setting on its default (Framework: Other, no build command, output directory blank).
3. Open the Vercel URL in Safari on your iPhone, tap Share, then Add to Home Screen.

## Updating recipes later
Replace index.html, change VERSION in sw.js (for example bruo-v11), and push. Vercel redeploys, and the app on your phone refreshes next time it is opened with internet.
