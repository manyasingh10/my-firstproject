# HerHorizon SafeRoute

A discreet SafeRoute web prototype with a calculator-style disguise, shelter directory, live GPS/map interface, safe transit flow, support tools, guardians, shelter admin controls, and emergency SOS UI.

## Run locally

Open `index.html` in a browser. For GPS/geolocation features, use a local HTTPS/localhost server rather than opening the file directly.

## Structure

- `index.html` — all page markup and modals
- `css/style.css` — styles extracted from the original single-file prototype
- `js/state.js` — APP_STATE and shelter demo data
- `js/calculator.js` — calculator and stealth-code unlock
- `js/stealth.js` — disguise/quick-exit/passcode functions
- `js/gps.js` — browser geolocation and coordinate UI
- `js/map.js` — Leaflet map, markers, corridors, layers
- `js/shelters.js` — shelter cards, filtering, walking simulation
- `js/transit.js` — transit, bed hold, voucher flows
- `js/support.js` — support chat, calls, silent beacon
- `js/admin.js` — shelter capacity/admin matrix
- `js/safety.js` — siren, strobe, fake call, SOS
- `js/ui.js` — portal navigation, guardian coordinate broadcast, toast

## External dependency

Leaflet 1.9.4 is loaded from unpkg in `index.html`. The map tiles use ArcGIS World Street Map as in the original prototype.

> This repository is a frontend prototype. The SOS, SMS/call, guardian broadcast, shelter availability, driver verification, and transit dispatch shown in the UI are demo behaviors unless connected to real backend/services.
