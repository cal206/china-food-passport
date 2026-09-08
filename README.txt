CHINA FOOD PASSPORT
===================

What this is
------------
A free, self-contained iPhone-friendly Progressive Web App (PWA) for your China trip.

Features
--------
- 39 local foods across Beijing, Xi'an, Chengdu, Chongqing, Zhangjiajie, Fenghuang, Guilin and Yangshuo
- Tried checkbox
- Score out of 10
- Photo for each dish
- "What is it?" description and ordering tip
- Personal notes
- Search + city filters
- Progress and average rating
- Offline support after first load
- Export/import backup

FREE GITHUB PAGES SETUP
-----------------------
1. Create a free account at github.com if you do not already have one.
2. Create a new PUBLIC repository, e.g. china-food-passport.
3. Upload ALL files from this folder to the repository root:
   index.html
   manifest.webmanifest
   sw.js
   icon-192.png
   icon-512.png
4. Open repository Settings > Pages.
5. Under "Build and deployment", choose "Deploy from a branch".
6. Select branch "main" and folder "/ (root)", then Save.
7. GitHub will show you your live site address after deployment.

ADD TO IPHONE HOME SCREEN
-------------------------
1. Open the live GitHub Pages URL in Safari.
2. Tap Share.
3. Tap "Add to Home Screen".
4. Make sure "Open as Web App" is enabled (if shown).
5. Tap Add.

DATA / PRIVACY
--------------
Your checkboxes, scores and notes are stored locally in your browser.
Photos are stored locally in the browser's IndexedDB.
Nothing is uploaded by this app.

IMPORTANT: clearing Safari website data can erase local app data.
Use "Export backup" occasionally. The backup includes your photos.

UPDATING THE APP
----------------
If you later replace index.html with a newer version, your saved trip data should remain because it is stored separately in browser storage.

FILES
-----
index.html            Main app
manifest.webmanifest  Home-screen/PWA settings
sw.js                 Offline cache
icon-192.png          App icon
icon-512.png          App icon
