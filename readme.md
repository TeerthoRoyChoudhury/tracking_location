🌍 Project Overview

This project visualizes the approximate geographical region associated with a phone number on an interactive map using Python. It combines phone number metadata with geocoding and map visualization to display a representative location.

⚠️ Note: This is not real-time GPS tracking. The location shown is based on number registration / telecom region, not the user’s live position.

✨ Features

📞 Extracts country & region from a phone number

📡 Identifies telecom carrier

🗺️ Converts region name into latitude & longitude

🧭 Displays the location on an interactive Leaflet map

💾 Saves the map as an HTML file viewable in any browser

🛠️ Tech Stack

Python 3.11

phonenumbers – phone number parsing & metadata

OpenCage Geocoder API – text-to-location geocoding

folium – interactive map generation

OpenStreetMap – map tiles

▶️ How It Works

Parse phone number using phonenumbers

Extract region & carrier

Convert region name to coordinates via OpenCage API

Plot the coordinates on a Folium map

Save the output as an HTML file 

## 📍 Sample Output

![Phone location map](image/Screenshot%202025-12-28%20122149.png)
