# Tube Pulse London — v2

Personal, independent mobile-first Progressive Web App. Not affiliated with Transport for London.

## Install on iPhone

1. Extract the zip. Publish the contents of the `tube-pulse` directory (including `index.html`, `sw.js`, icons, and manifest) to an HTTPS host such as GitHub Pages or Netlify.
2. Open that HTTPS site in iPhone Safari.
3. Use Share → Add to Home Screen. This is a PWA, not an App Store .ipa, so it cannot install by opening the zip directly.

## Features

- 20 curated major stations; filter and search; saved favorites kept locally.
- Interactive *simplified and not geographically accurate* network schematic; does not show all stations, connections are illustrative.
- TfL live arrivals (auto refresh about 45s for open station) and network statuses, subject to network connectivity and API limits.
- Experimental non-live, non-measured crowding planner based on generic category/rush-hour heuristics. This is not live passenger load, measured NUMBAT values, station queue estimates, or a guarantee of seat availability.
- TfL stop metadata display for available accessibility properties. Absence of a property does not establish step-free access.
- Station highlights and links to maps and official TfL journey planning.

## Future integration

For real research-grade historical estimates, import and normalize TfL NUMBAT (station flows, boarders, link loads by 15-minute intervals and day type). If live train occupancy data becomes available, display it separately from forecasts and label its freshness and source. TfL Unified API: https://api.tfl.gov.uk/ . NUMBAT: https://tfl.gov.uk/info-for/open-data-users/our-open-data .

For native App Store/iOS installation, this design can be ported to SwiftUI; v2 ships as a PWA.
