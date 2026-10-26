# Tube Pulse London — v3

An independent personal iPhone-compatible PWA using TfL public data. London-only in this release; all 20 existing curated stations remain.

## Replace your GitHub Pages version

1. Unzip this download. Open the inner `tube-pulse` directory.
2. On GitHub, open your **existing** `tube-pulse-london` repository and upload the files inside that directory to the **root** of the repository. Commit the changes, replacing the older files with the same names.
3. Keep the existing repository, username and Pages settings; your website URL remains unchanged.
4. Revisit the site on your iPhone with internet connected. If the Home Screen copy still displays v2, open the page in Safari and reload it, or remove/re-add the Home Screen shortcut after refreshing.

## Version 3

- Keeps the featured 20-station search, favorites, TfL line status and live arrival API integration.
- Adds expanded platform filter, a clearer train board and refresh action.
- Adds map zoom to the existing **illustrative** clickable 20-station schematic, with a link to TfL's **full official map**. This is *not* a full interactive map of every Tube station.
- Adds links for station-local cafes, food, attractions and shops via current Google Maps searches (not a verified or pre-fetched nearby-places database).
- Adds direct links for official TfL step-free guidance, status updates, and journey planning. Metadata may be incomplete.
- Keeps transparent time-of-day crowding estimates using an **illustrative heuristic**. This does not represent live train occupancy, observed passenger counts, actual wait time to enter a platform, or predictions calibrated to NUMBAT data.

**Testing:** Live TfL arrivals and stop metadata need online testing on the deployed site. Requests can fail, be rate-limited, or be incomplete. Official travel information takes precedence. No native SwiftUI/IPA is included.

© TfL for the public API data when retrieved; independent project, not affiliated with TfL.
