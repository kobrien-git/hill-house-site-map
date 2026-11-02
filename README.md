# Hill House, Corracunna – site map

Interactive briefing map of the existing house and site at Hill House, Corracunna, Mitchelstown, Co. Cork.

It's a static page (Leaflet), with no build step. Open `index.html` through any web server, or publish the folder with GitHub Pages (Settings → Pages → deploy from branch `main`, folder `/root`).

## Contents
- `index.html`: the map and the info panel.
- `data/data.js`: the survey outlines, the townland boundary, overlay bounds, and photo locations (WGS84).
- `img/`: the 2021 drone image and the historic map screenshots, georeferenced by hand.
- `photos/`: drone photo thumbnails (2021 and 2026).

## Caveats
- The survey outlines are traced from the March 2026 measured survey (.dwg) and placed by eye, so their position is about ±1-2 m. Use the .dwg for dimensions.
- The historic maps are screenshots from Tailte Éireann (© Tailte Éireann / Government of Ireland), for indication only.
