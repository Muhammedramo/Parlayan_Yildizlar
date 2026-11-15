# Mars Surface Explorer

An interactive map for exploring terrain and illustrative environmental conditions across **Elysium Planitia on Mars**.

[![NASA Space Apps Challenge 2026](https://img.shields.io/badge/NASA_Space_Apps-Challenge_2026-0B3D91?style=flat-square&logo=nasa&logoColor=white)](https://www.spaceappschallenge.org/)
[![Team Shine Stars](https://img.shields.io/badge/Team-Shine_Stars-FF4500?style=flat-square)](https://www.spaceappschallenge.org/2026/find-a-team/shine-stars/)

## Features

### Map layers

- **Optical** — Viking MDIM21 imagery.
- **Topographic** — MOLA/HRSC shaded relief.
- **Thermal** and **Radiation** — illustrative regional models.

Pan and zoom around the map, then select a point to inspect its readings. Set a current location and a destination to view the estimated surface distance between them.

### Point readings

- Elevation from the NASA MOLA/HRSC service.
- Surface appearance sampled from the optical map.
- Pressure estimated from elevation.
- Temperature and radiation values from illustrative map models.
- Hazard indicators based on the displayed temperature and radiation estimates.

The wind and dust overlay is illustrative, not live weather data or a forecast. Model readings and hazard indicators are for exploration only; they are not operational safety guidance. NASA elevation lookups require an internet connection. Some browsers may restrict optical pixel sampling when the page is opened directly as a local file.

## Run the map

No installation or build step is required:

1. Download or clone this repository.
2. Keep the `assets` folder alongside `index.html`.
3. Open `index.html` in a modern browser.

## The team

**Shine Stars (Parlayan Yıldızlar)** is a team of six engineering students participating in the NASA Space Apps Challenge. The team brings together a shared interest in engineering and space exploration.

[Visit the Shine Stars team page](https://www.spaceappschallenge.org/2026/find-a-team/shine-stars/)
