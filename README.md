# Haze Watch SG

A single-page monitor for Singapore haze and ASEAN weather.

- **Haze tab:** 24-hour PSI and 1-hour PM2.5 for the North, South, East, West and Central areas, from the National Environment Agency via [data.gov.sg](https://data.gov.sg).
- **Weather tab:** Singapore conditions and a 4-day outlook, plus 12 ASEAN cities, from [Open-Meteo](https://open-meteo.com) (CC BY 4.0).

Data is fetched in the browser when the page loads and every 15 minutes after that. There is no build step and no API key.

## Deploy on Vercel

1. Import this repository in Vercel.
2. Leave **Framework Preset** as *Other*, with no build command and no output directory.
3. Deploy. Vercel serves `index.html` at the site root.

## Run locally

Open `index.html` in a browser, or serve the folder with any static server, for example `npx serve .`.
