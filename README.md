ANNADANAM — ADVANCED REAL MAP + GPS + RELIABLE DIRECTIONS

Run:
1. Unzip this folder.
2. Open index.html in Chrome/Edge, preferably through localhost or HTTPS for GPS.
3. Allow Location permission when asked.

Directions:
- Every Meal Seva stores its exact latitude/longitude.
- Get Directions uses Google Maps Directions with the exact pin as destination.
- If live GPS is available, it is passed as the starting point.
- If GPS is unavailable/denied, Google Maps still opens to the exact destination.
- The app navigates in the current tab instead of window.open, avoiding popup blockers.
- If an old Seva has no coordinates, the app falls back to a Google Maps location search.

Map:
- Leaflet + OpenStreetMap.
- Tap map to place a Seva pin.
- Drag pin to refine it.
- Use Live GPS to set the pin.
- Published Sevas are shown on the live map.

Important:
This demo stores community posts in browser localStorage, so posts are not globally shared between different devices. A production public service needs a shared backend/database, authentication, moderation, and secure storage.
