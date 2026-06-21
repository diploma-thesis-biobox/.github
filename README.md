# BioBox

**Intelligent, automated plant chamber — a cyber-physical HTL Diploma Thesis.**

BioBox is a compact, sensor-driven growth chamber that closes the full control loop:
**measure, interpret, regulate, document, predict.** It combines embedded control,
a web platform, a relational data model, computer-vision plant analysis, and a
data-supported digital twin into one real, demonstrable system.

---

## Overview

- Measures air temperature/humidity, soil moisture, soil temperature, and light
- Regulates LED, fan, PTC heater, irrigation, and nutrient dosing locally and deterministically
- Stores, historises, and visualises all telemetry in a central web platform
- Analyses top-down plant images (leaf area, canopy cover, greenness, stress indicators)
- Forecasts growth, water need, and stress risk via a grey-box digital twin

---


**Design principle:** each layer does only what it is technically suited for.
Safety and plant survival never depend on the cloud or the browser — the ESP32-S3
keeps regulating autonomously if the network or backend goes down.


---

## Tech stack

`ESP32-S3` · `Node.js` · `Express` · `PostgreSQL` · `React` · `TypeScript`
`Tailwind CSS` · `Chart.js` · `Python` · `OpenCV` · `WebSocket` · `REST/HTTPS`

---

## Team

| Member | Department | Responsibility |
|--------|------------|----------------|
| **Grid Tanushi** | Electronics & Hardware | Sensorik, actuator/MOSFET board, power, ESP32 firmware, local safety logic |
| **Edona Peraj** | Web Development & Design | API contract, backend, PostgreSQL schema, dashboard, roles |
| **Atida Ashta** | Data Science | Camera pipeline, segmentation, growth metrics, digital twin, optimisation |

---

*An interdisciplinary automation project — built to be defended, documented, and reproduced.*
