# Tamil Nadu Weather Intelligence V6

Mobile-friendly weather dashboard for Tamil Nadu with model forecast, radar, satellite, district/city search, storm/low-pressure screening, and Instagram-ready 4:5 PNG reports.

## Deploy with GitHub Pages
1. Create a new GitHub repository, e.g. `tn-weather-intelligence`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** branch and **/(root)**, then Save.
6. GitHub will provide a public HTTPS URL.

HTTPS is important for the device GPS Location permission. Opening the HTML directly from a phone download (`content://`/`file://`) may block browser geolocation.

## Data sources
- Forecast/model: Open-Meteo
- Map: OpenStreetMap
- Satellite basemap: Esri World Imagery
- Radar: RainViewer when available
- Official India warnings/advisories: IMD

The app keeps model forecast, radar observation, and official IMD warnings separate. Model-derived storm/low-pressure screening is experimental and is not an official cyclone warning or forecast track.

## Instagram report
Use **Instagram 4:5 Report**. It generates a 1080×1350 PNG suitable for an Instagram portrait post. The report includes location, timestamp, current conditions, rain probability, next 6 hours, 24-hour rain outlook, atmosphere indicators, wind, pressure and 7-day outlook.
