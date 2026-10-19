# Split Log v2.0

Upgrade to the existing GitHub Pages app. Includes editable four-day plan, rest timer, progress charts, calendar, previous sets, history, and JSON backups.

## Important: protect your data

On your existing Split Log Home Screen app, open Settings → Export backup and save the JSON to Files **before uploading the update**. Do not remove the existing Home Screen icon, clear website data, or uninstall the app. The app keeps the original localStorage key `splitlog-pwa-v1`, including saved sessions and drafts. Existing sessions stay intact when editing exercises.

## Update GitHub Pages

Upload `index.html` and `service-worker.js` into the root of the existing `apple99222004-lab/Split-Log` repository, replacing the old files. `manifest.webmanifest` and `icon.svg` are included for completeness, and can be uploaded if missing. Do not upload the ZIP itself. Commit directly to `main`. GitHub Pages should redeploy automatically. Reopen the existing Home Screen icon; if the app is cached, fully close/reopen or refresh Safari after deployment.

No cloud sync. iOS Safari and Home Screen installations can have separate local storage. If records do not appear, use Settings → Import backup **only after exporting any records on the new instance**.
