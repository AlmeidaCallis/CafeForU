☕ CafeForU

"We brew it, you love it.

"CafeForU is a high-performance, open-source cafe discovery MVP built for coffee enthusiasts. Unlike traditional map apps, it leverages the OpenStreetMap (OSM) ecosystem to provide a lightning-fast, privacy-conscious experience without the need for expensive API keys or tracking.

🚀 Pro Features

1. Smart Discovery Engine: Uses the Overpass API to pull live data for Cafes, Restaurants, and Bakeries within a customizable 1km–10km radius.
2. Dual-Source Resilience: Features an automatic Failover Engine. If the primary data server is busy, the app instantly generates realistic "nearby" mock data to ensure the UI never stays empty
3. Real-Time Brew Tracker: Integrated Geolocation API follows your movement with a pulsing blue dot, updating nearby results as you walk.
4. Professional UI/UX:

- Glassmorphism Design: Modern, semi-transparent interface that adapts to mobile and desktop.Espresso
- Dark Mode: Toggle between light and dark map themes for late-night coffee runs.Interactive
- Sidebar: A collapsible list showing ratings, distances, and one-tap "Fly-To" map navigation.

5. Local Persistence: Saves your recent search history to your browser's local storage for quick access later.

🛠️ Technology Stack

Component Technology

1.  Map Rendering Leaflet.js (No API Key Required)
2.  Map Tiles OpenStreetMap / CartoDB
3.  Data Source Overpass API (OSM Data)
4.  Geocoding Nominatim (City to Lat/Lon conversion)
5.  Styling Vanilla CSS3 (Custom Coffee Palette)
6.  Icons Font Awesome 6

📂 Installation & Usage

This project is a Zero-Dependency MVP. You do not need npm, react, or any build tools.

1. Clone/Copy: Save the index.html file to your local machine.
2. Logo Setup: Ensure the logo image is accessible (the provided code uses a hosted link to your logo).
3. Launch: Open the file in your browser or use the VS Code Live Server extension.
4. Allow Location: When prompted, allow "Location Access" to see cafes in your immediate vicinity.

☕ Customization

To change the default starting location from Mumbai, find the init() function and modify the coordinates:

JavaScriptmap = L.map('map').setView([YOUR_LAT, YOUR_LON], 14);

📝 License

This project is open-source and free to use for personal or commercial projects. Built with ❤️ for coffee lovers.
