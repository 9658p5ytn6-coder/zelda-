QUEST MAP — iPhone setup

WHAT IT DOES
- Uses your iPhone's live GPS location.
- Searches for a destination.
- Draws a driving route and follows your position.
- Shows a compact next-step navigation panel.
- Re-routes if you get far off the route.
- Includes "APPLE MAPS" to hand the destination to Apple's native Maps app for full voice/turn-by-turn navigation.
- Retro 1980s fantasy quest styling; it does not copy Nintendo artwork.

IMPORTANT
iPhone Safari only grants live location to secure HTTPS websites (or localhost), so opening index.html directly from the Files app is not enough for GPS.

FREE HOSTING — GITHUB PAGES
1. Create/sign in to a GitHub account.
2. Create a new PUBLIC repository, e.g. quest-map.
3. Upload index.html, manifest.webmanifest, and sw.js from this folder.
4. Repository Settings → Pages.
5. Under "Build and deployment", choose "Deploy from a branch".
6. Choose main / (root), then Save.
7. Open the resulting HTTPS Pages address in Safari on your iPhone.
8. Tap Share → Add to Home Screen.
9. Open Quest Map from the new icon.
10. When asked, allow Location access.

USAGE
1. Type an address/place.
2. Tap GO.
3. Keep the page open while navigating.
4. For Apple's full spoken turn-by-turn navigation, tap APPLE MAPS.

NOTES
This prototype uses:
- OpenStreetMap map tiles/data.
- Nominatim place search.
- OSRM public demo routing.
These public services are excellent for personal/testing use but are not a production backend for a large public app.

No API keys are stored in this project.
