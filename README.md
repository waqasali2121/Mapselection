# Tactical Zone & Search Corridor Planner

An interactive tactical search zone & strike corridor planning application built with **Leaflet.js**, **OpenStreetMap**, **Esri World Imagery**, and **Turf.js**. 100% free with **no API keys or credit card required**.

## 🚀 Features

- **Point Selection (Alpha & Bravo):** Click anywhere on the map or drag pins to position Start (Alpha) and End (Bravo/Target) operation points.
- **Dynamic Tactical Corridor Buffer:** Generates a real-time highlighted translucent polygon around the route line between points.
- **Adjustable Search Radius:** Adjust corridor buffer width dynamically from 50m up to 5,000m (5km).
- **Multiple Tile Imagery Layers:**
  - Dark Tactical Basemap (CARTO)
  - High-Resolution Satellite Imagery (Esri)
  - Standard OpenStreetMap
  - Topographic Map (OpenTopoMap)
- **Live Operations HUD:** Displays direct distance, total search area (sq km), corridor perimeter, and center grid coordinates.
- **Geocoding & Location Search:** Integrated free Nominatim geocoder.
- **GeoJSON Export:** Download tactical zone boundaries directly as standard GeoJSON for GIS applications.

## 🛠️ Tech Stack

- HTML5 / CSS3 / JavaScript (ES6)
- [Leaflet.js](https://leafletjs.com/) - Interactive Map Engine
- [Turf.js](https://turfjs.org/) - Geospatial Analysis & Geodesic Buffering
- OpenStreetMap & Esri World Imagery - Free Map Tiles
- Vercel - Instant Static Deployment

## 🌐 Deploy to Vercel

1. Push this repository to GitHub.
2. Go to [Vercel](https://vercel.com) and click **"Add New Project"**.
3. Import your GitHub repository.
4. Click **Deploy** (No build command or environment variables required).

## 📄 License

MIT License
