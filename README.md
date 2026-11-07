# Meghalaya & Kamakhya Expedition Map (Dec 2026)

Interactive Google Map + day-wise itinerary for 15 travelers.

## Run
`node server.js` (Railway auto-detects via Dockerfile / `npm start`)

## Railway Variables
- `GOOGLE_MAPS_API_KEY` (required)
- `GOOGLE_MAPS_MAP_ID` (optional, default `DEMO_MAP_ID`)

## Google Cloud – APIs required on the key
- Maps JavaScript API
- Routes API (road routes, re-route) — falls back to Directions API, then straight lines
- Places API (New) (search bar) — falls back to legacy Places API

## Features
- Google Maps pins per day, road routes per day + full circuit, day distance/time
- Search bar with glowing pulsing marker for searched place
- Re-route: inserts searched place into chosen day, optimises order, shows distance/time change + new order
- Navigate day / new route in Google Maps app, live GPS location
