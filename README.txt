VOLTARIS - Electricity Theft Risk Intelligence
================================================

FILES
  index.html              the whole app (screens, styles, code)
  manifest.webmanifest    lets phones and PCs install it as an app
  sw.js                   lets it open offline after the first visit
  icons/                  app icons

TRY IT ON YOUR COMPUTER
  Double-click index.html. (Install and offline need a web link, see below.)

PUT IT ON THE INTERNET WITH GITHUB PAGES (free)
  1. Make a public repository named voltaris at github.com.
  2. Add file > Upload files. Drag EVERYTHING inside this folder:
     index.html, manifest.webmanifest, sw.js and the icons folder.
  3. Commit changes.
  4. Settings > Pages > Branch: main, folder: / (root) > Save.
  5. Wait 1-2 minutes. Your link: https://YOURUSERNAME.github.io/voltaris/
  To update later: upload the new files again (same names) and commit.
  Then press Ctrl+Shift+R on the site to see the new version.

INSTALL AS AN APP (after it is on a link)
  Android (Chrome):  menu (3 dots) > Install app
  iPhone (Safari):   Share > Add to Home Screen
  Windows/Mac (Chrome or Edge): install icon at the right of the address bar

LOGIN
  This is a prototype. Any email and password sign you in.
  All consumers, scores and zones are sample data.

NEXT STEP: REAL DATA
  Connect your Python/Flask detection code and load the scores with
  fetch("/api/consumers") instead of the sample list in index.html.
