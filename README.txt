Quack Harbor v1.8.1

Files: index.html, sw.js, manifest.webmanifest, peerjs.min.js (for Play together), and four icon PNGs.
Put all of them in the top folder of a GitHub Pages repo (or any static host).

Updating later: replace the files, and the service worker picks up the
new index.html automatically the next time a tablet opens the game online.
Each release bumps CACHE in sw.js and app-version in index.html.
Custom character art goes in a folder named art (see the Art Kit).

Saves (coins, upgrades, photos) live on each tablet, per web address.

What's new in v1.8
- Bridges: from level 4, neighbouring islands can be joined by a footbridge. A duck may
  cross to the dock next door, or turn back halfway. Boats sail underneath.
- Harbor life: jumping fish (sail through for coins), a seagull that drops gifts,
  and messages in bottles.
- Captain's Log (the Missions button on the home screen): three daily missions,
  Today's Voyage (one special level a day), and the Seashell Trail with five boats
  that can only be earned. Eight new stickers. Still no ads and nothing to buy.
- Phones: menus fit short sideways screens, a slimmer HUD upright, and the close-up
  view switches on by itself when the whole board would be too small to play.

v1.8.1 balance (from the first play log)
- Grown-up mode, later loops: 4 hearts in the second loop, 3 after that.
- After the story, replayed levels and pirate rematches pay less than new levels.
- Starfall's own gems and coins no longer refill the SUPER meter.
- Snow Match for grown-ups: 5 misses and a longer peek (was 3 and 1.5 s).
- Play log: version, hearts, bridges, bridge ducks, fish, gifts, daily voyage and
  missions columns; quits under 5 seconds are no longer logged.
