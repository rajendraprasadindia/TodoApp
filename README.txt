HOW TO RUN (Android + Desktop)

1) Unzip this folder somewhere (Downloads is fine).
2) Desktop: double-click index.html to open in a browser.
3) Android: install a 'Simple HTTP Server' app (or Termux + `python -m http.server 8000`),
   point it at this folder, then open the shown http:// address in Chrome.
4) You can add, check-off, delete tasks, and export/import JSON.

Optional PWA: Since a service worker is included, when served over http(s) you can
'Install' the app from Chrome's menu and use it offline.
