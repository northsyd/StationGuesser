# Station Guesser — GitHub Pages version

This version runs fully in the browser, so it works on GitHub Pages with no Express/Replit backend.

## Upload to GitHub Pages

1. Upload these files to your repository:
   - `index.html`
   - `stations.js`
2. In GitHub, go to **Settings → Pages**.
3. Set the source to your main branch/root folder.
4. Open the Pages URL.

## Add your full station dataset

Replace the array in `stations.js` with your full `ALL_STATIONS` data from Replit.

Each station needs this shape:

```js
{ name: "Central", lat: -33.8823, lon: 151.2065, mode: "Train", state: "NSW" }
```

The game supports:
- NSW / VIC / any-region rounds
- autocomplete station names
- distance feedback using the Haversine formula
- hints
- skip
- localStorage session saving
