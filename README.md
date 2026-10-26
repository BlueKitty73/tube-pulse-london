# Tube Pulse London v5 — GitHub Pages iPhone PWA

Upload **the contents** of this folder directly into the root of the same GitHub Pages repository, overwriting the v4 files. Keep `index.html` at repository root. GitHub Pages: Settings → Pages → Deploy from branch → main → /(root).

Reload in Safari after deployment. On iOS the Home Screen app may temporarily display its previously cached shell: close it, open the GitHub Pages URL in Safari, refresh, then relaunch. Favorites in local storage are retained if you keep the same site URL.

## Features
- London-only guide to the original **20 featured stations**; accessible offline after first successful loading.
- TfL live station arrivals with platform/destination when supplied; textual reported train locations are **not GPS**.
- London street map via Leaflet/OpenStreetMap; original schematic retained. Map overlays load geographic paths from TfL's line sequence endpoint when available, otherwise dashed illustrative connections remain.
- From/to journey planner through TfL JourneyResults endpoint with route preference and optional step-free-to-platform request.
- TfL fare-to endpoint; only display usable returned monetary fare figures. If no supported result, refer to official fare finder instead of guessing.
- TfL line status and reason text, on-demand refresh.
- Station access metadata and links to TfL's current step-free/lifts guidance, attractions and nearby place search.
- Preserves labeled illustrative crowding patterns; **NOT yet derived from NUMBAT data**. Link to official source provided.
- Cached local site assets/offline station guide and saved favorites. Map tiles, TfL APIs and external links require connectivity.

## Reality checks
This is a personal prototype; test TfL endpoint responses from your hosted site. TfL APIs may impose key/rate limits, and API registration may be necessary. Never embed a private API key in a public GitHub Pages repository. Real-time train occupancy, precise real-time passenger wait times, step-free guarantees and exact fares without confirmation are not provided. Where unavailable, the app should say so instead of fabricating a value.

Sources: https://tfl.gov.uk/info-for/open-data-users/api-documentation , https://tfl.gov.uk/info-for/open-data-users/our-open-data , https://api-portal.tfl.gov.uk/ . OpenStreetMap tiles require internet and proper attribution.
