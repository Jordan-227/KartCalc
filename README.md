# KartCalc 🏎️

A go-kart **setup & conditions tracker**. Log your chassis setup and how the kart
performed, see live weather + air density for your circuit, get a day-ahead
warnings calendar, and receive setup recommendations that combine kart-tuning
principles with your own past data.

## Features

- **Conditions dashboard** — live weather for any circuit (via [Open-Meteo](https://open-meteo.com), free, no API key).
- **Air density ("air thickness")** — calculated from temperature, humidity and pressure, with what it means for engine power and jetting.
- **Warnings calendar** — a day-ahead agenda of rain windows, temperature swings, air-density dips and strong wind.
- **Session logging** — camber, caster, front/rear track width, ride heights, axle hardness, tyre pressures, compound, gearing, jetting, plus conditions and lap times.
- **History** — every session, filterable, click to edit.
- **Recommendations** — directional setup advice for the day's grip/density, issue-specific fixes (understeer, oversteer, hopping, overheating, low grip, lost power), and your fastest proven setup in similar conditions.
- **Backup** — export/import all data as JSON. Data is stored locally in your browser.

## Run it

Just open `index.html` in any modern browser — no build step, no server.

## Deploy

It's a single static file, so it deploys anywhere:

- **GitHub Pages** — push to GitHub and enable Pages on the `main` branch.
- **Vercel** — import the repo (framework preset: *Other*), no build command needed.

## Notes

Setup tips are **starting heuristics** based on common sprint-kart tuning — direction
can vary by chassis and tyre. The tool gets more accurate the more you log: it learns
your fastest proven setups per track and condition.
