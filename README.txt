OJT HOURS TRACKER — OFFLINE PWA

WHAT THIS IS
------------
A small installable web app for iPhone, iPad, Android, Mac, or PC.
After the first successful load from an HTTPS website, the app can work offline.

FEATURES
--------
- Add OJT hours by date and category
- Automatic on-device saving using IndexedDB
- Edit/delete entries
- Current-day, current-week, and all-time totals
- Previous/next weekly summaries
- Print / Save Weekly Report
- Export weekly CSV
- Export full JSON backup
- Restore from a JSON backup
- Separate data for each person's device/browser
- Offline caching via service worker

IMPORTANT
---------
For the offline install feature to work, the files must be served from HTTPS
(or localhost while testing). Opening index.html directly from the Files app
will not install the service worker.

EASIEST WAYS TO PUBLISH
-----------------------
Option 1: GitHub Pages
1. Create a new GitHub repository.
2. Upload ALL files/folders from this package to the repository root.
3. In the repository, open Settings > Pages.
4. Choose "Deploy from a branch".
5. Select the main branch and root folder.
6. GitHub will provide an HTTPS address.
7. Open that address in Safari on the iPhone.

Option 2: Cloudflare Pages / Netlify
Upload the folder as a static site. Both can provide an HTTPS URL.
No server code or database is required.

INSTALL ON IPHONE / IPAD
------------------------
1. Open the HTTPS app address in Safari.
2. Tap the Share button.
3. Choose "Add to Home Screen".
4. Tap Add.
5. Launch "OJT Tracker" from the Home Screen once while online.
6. It can then continue working without internet access.

SHARING WITH OTHER PEOPLE
-------------------------
Send them the same HTTPS link.
They install it on their device.
Their OJT records stay on their device and are NOT shared with yours.

BACKUPS
-------
Use "Export Backup" periodically.
The JSON file contains all saved entries.
Use "Import Backup" to restore records to another device.

DATA / PRIVACY
--------------
There is no cloud database in this version. OJT records stay in the browser's
on-device storage unless the user exports them.

Clearing website data, deleting the site/app data, or some device reset/
restore operations can remove local data, so keep periodic exported backups.

FILES
-----
index.html
manifest.webmanifest
sw.js
icons/icon-192.png
icons/icon-512.png
icons/icon-512-maskable.png
README.txt
