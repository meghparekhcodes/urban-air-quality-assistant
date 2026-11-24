# Urban Air Quality Assistant

A simple, location-aware assistant for families navigating winter smog and urban air pollution. It provides air-quality context, practical daily suggestions, and indoor-air guidance based on your city and routine.

## Live demo

[Open the Urban Air Quality Assistant](https://meghparekhcodes.github.io/urban-air-quality-assistant/)

## Features

- Air-quality snapshot and guidance for a chosen city
- Daily suggestions tailored to commute, cooking fuel, household needs, and priorities
- Indoor-air tips and lower-emission alternatives
- Demo mode for exploring the app without live data
- Responsive layout for desktop and mobile

## Data and guidance

Live air-quality readings are model-based estimates from Open-Meteo, not direct monitoring-station measurements. If live data is unavailable, use **Try demo data** to explore sample information.

Recommendations are general guidance. Impact notes are directional estimates, not guaranteed reductions in exposure or emissions. Follow local public-health alerts and consult a qualified professional for health concerns.

## Run locally

This is a static page with no build step. Open `index.html` in a browser, or run a local server:

```bash
python3 -m http.server 8000
