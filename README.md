# Tube Pulse London v4 — Street Map Edition

## New
- Actual geographical London street map (Leaflet + OpenStreetMap), with all 20 featured station pins.
- Line filters and approximate dotted connections across these featured stations.
- Switch between **London street map** and the original **Tube diagram**.
- Tap a station marker and **View next trains** for the existing arrival board.

## GitHub Pages upgrade
1. Unzip this file.
2. In your existing repository, upload all files **inside** the `tube-pulse` folder, replacing the originals in the repository root.
3. Commit. Keep the same GitHub Pages Settings → Branch → main / (root).
4. Refresh on Safari after Pages publishes the new version; if cached, close and reopen the Home Screen app.

## Map caveats
- No Google Maps API key needed; Leaflet loads from CDN.
- OpenStreetMap background map tiles require an internet connection and are used only for interactive viewing, not offline tile bulk downloads.
- Station locations are approximate point coordinates, *not validated entrance locations*.
- **Dashed rail connections are approximate straight lines between only the featured stations** and must not be used as a real route, accurate track alignment, or a list of all intermediate stops.
- Map © OpenStreetMap contributors, attribution is displayed inside the map. OpenStreetMap tile servers have fair-use requirements; use a commercial map-tile provider if significant traffic develops.
- Existing favorites and TfL arrival functions are preserved from v3.
- Live map loading and TfL predictions depend on working third-party services and should be tested after GitHub deployment.
