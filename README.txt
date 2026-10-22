KTC PWA complete package (PNG icon)

APP ICON:
- icon-192.png
- icon-512.png
Both were created from the icon image you uploaded.

CONTACT PROFILE PHOTOS:
Put each photo in the SAME folder as index.html and use these exact names:
- PRIYA.jpg       -> PRIYA contact
- BUBU.jpg        -> BUBU ❤️ contact
- DAD.jpg         -> DAD contact
- BHAI.jpg        -> BHAI contact
- DELHI-Transport-Corporation.jpg -> KTC / DELHI Transport Corporation contact

For each profile photo, JPG or PNG works only if the app code is set to that exact extension. In the current code the personal contacts look for the JPG names above. To keep it simple, use .jpg for profile photos. The app icon specifically uses PNG.

GITHUB PAGES:
Upload all files to the SAME repository folder as index.html (normally the repository root):
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png
- profile JPG files listed above
- keep any other assets your existing project needs

Then commit changes and wait for GitHub Pages to redeploy. Since the app may already be installed, close/reopen it; if the old icon remains, uninstall the installed PWA and reinstall it after deployment.

NOTE:
Chat and booking persistence in this package is browser-local, not a server backend. Profile photos are static assets served from GitHub Pages.
