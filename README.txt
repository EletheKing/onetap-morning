OneTap Icon Update v3

Files included:
- index.html (links new manifest + apple-touch icon, unregisters old SW, registers sw-v4.js)
- manifest-v3.json (uses icon-192-v3.png & icon-512-v3.png, start_url .?v=10)
- sw-v4.js (cache onetap-v4, precaches icons & manifest)
- icon-192-v3.png
- icon-512-v3.png
- apple-touch-icon-v3.png (180x180)

How to deploy:
1) Upload ALL files to your repo root (overwrite existing).
2) Commit, wait ~60s.
3) On iPhone: delete old Homescreen app, then Settings → Safari → Advanced → Website Data → search github.io → delete entries.
4) Open https://eletheking.github.io/onetap-morning/?v=10 and add to Homescreen.
