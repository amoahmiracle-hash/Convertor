FIVE GRAINS CUP & SPOON CONVERTER — APP PACKAGE
=================================================

WHAT'S IN THIS FOLDER
  index.html        the app itself
  manifest.json      tells the browser it's installable, sets the icon/name
  service-worker.js  caches everything so it works with zero internet after first load
  icon-192.png / icon-512.png / icon-180.png   app icons

OPTION 1 — JUST OPEN IT (no install)
  Double-tap index.html. Works fully offline like before, but won't show
  up as an app icon on your home screen — it opens as a browser tab.

OPTION 2 — INSTALL AS AN APP (recommended)
  A phone browser will only offer "Add to Home Screen" as a real app
  (with its own icon, no browser bar) if these files are served over
  the web at least once — after that it runs 100% offline.

  Easiest free hosting (same idea as your notes storefront deploy):
    1. Create a new GitHub repository, upload all 5 files in this folder.
    2. Settings → Pages → deploy from the main branch → save.
    3. GitHub gives you a link like:
       https://yourname.github.io/cup-converter/
    4. Open that link on your phone in Chrome (Android) or Safari (iPhone).
    5. Tap the menu → "Add to Home Screen" / "Install app".
    6. The Cup Convert icon appears on your home screen. From then on
       it opens instantly and needs no internet at all.

  Render.com works the same way as a static site if you'd rather use that.

OPTION 3 — TURN IT INTO A REAL ANDROID APK
  Once it's hosted anywhere (step above), go to https://www.pwabuilder.com,
  paste the link, and it will package it into a downloadable .apk you can
  install directly, no Play Store needed.

Nothing in this app ever contacts the internet or sends data anywhere —
hosting is only needed for that one-time "install" step.
