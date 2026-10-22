KTC Messenger PWA - GitHub Pages package

What changed:
- Removed the static unread “2” badge on the KTC chat.
- Fixed the in-app back action so it returns to the previous screen (chat -> home) once, without reopening the chat behind the scenes.
- Set saved transaction retention to six hours.
- Added manifest, service worker and app icons to support Chrome's installable PWA flow.

Important:
- This is still a front-end demo. Six-hour persistence currently uses localStorage on the same browser/device. It is NOT a server backend and will not sync between devices.
- Real server-side six-hour storage needs a configured backend such as Supabase, including project URL, keys, database table and security policies. Do not put a service-role key in browser code.
- GitHub Pages must be HTTPS. Upload every file in this package to the repository root (not just index.html). Keep any original image assets (such as profile.png or ticket images) that your project already uses.
- Open the deployed HTTPS link in Chrome. Use the install icon in the address bar or Chrome menu > Install app. If it doesn't appear immediately, refresh after the deployment completes.
