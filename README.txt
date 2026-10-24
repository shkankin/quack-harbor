Quack Harbor v1.0

Files: index.html, sw.js, manifest.webmanifest, and four icon PNGs.
Put all of them in the top folder of a GitHub Pages repo (or any static host).

Updating later: replace the files, and the service worker picks up the
new index.html automatically the next time a tablet opens the game online.
Each release bumps CACHE in sw.js and app-version in index.html.

Saves (coins, upgrades, photos) live on each tablet, per web address.
