# WatchSwipe Feed

Public content feed for the WatchSwipe app — brand profiles, editorial stories,
and the watch catalog. Served via GitHub Pages and fetched by every install.

`feed.json` is a full-snapshot envelope (`formatVersion`, `edition`, `publishedAt`,
`stories`, `watches`, `brands`). Bump `edition` on every publish. Do not hand-edit
in this repo — it is published from the app repo via `npm run feed:publish`.
