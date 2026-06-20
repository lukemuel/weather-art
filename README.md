# Atlas — Weather City Visualizer

A generative city scene driven entirely by real, live weather data. Type any city and watch it render as a moody, atmospheric skyline — sky, sun/moon, skyline lighting, and traffic all respond to what's actually happening there right now.

No API key required — built on [Open-Meteo](https://open-meteo.com/), a free weather + geocoding API.

## What it does

- Geocodes any city name and pulls live current weather (temperature, wind, cloud cover, precipitation, day/night)
- Renders a seeded procedural skyline — same city always generates the same skyline, scaled by real population data (bigger cities get denser, taller buildings)
- Sky color, lighting, and mood shift with temperature, cloud cover, and time of day
- Lit windows + a subtle glass shimmer sweep on buildings at night/day respectively
- A highway with detailed cars (sedans, SUVs, trucks) driving both directions, with headlights/taillights at night
- Real rain or snow falls if the city is currently experiencing it
- Thunderstorm conditions trigger actual screen-flash lightning
- Film grain + vignette for a cinematic finish

## Tech

Single HTML file — vanilla JS, Canvas 2D, no build step, no dependencies. Just open `index.html`.

## Try it

```bash
open index.html
```

Type a city, hit render, and compare a few — a clear day in Phoenix looks nothing like a stormy night in Hong Kong.
