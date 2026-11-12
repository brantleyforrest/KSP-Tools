# KSP-Tools: Kerbal Space Program Mission Suite

An open-source collection of interactive web-based calculators, orbital visualizers, and mission planning utilities designed for players of **Kerbal Space Program (KSP)**.

---

## Live Deployment

The interactive tools are accessible via GitHub Pages:  
**[https://brantleyforrest.github.io/KSP-Tools/](https://brantleyforrest.github.io/KSP-Tools/)**

---

## Overview

Setting up satellite constellations, planning interplanetary transfers, computing delta-V budgets, and executing precise vacuum landings require tricky calculations and spatial intuition. 

**KSP-Tools** provides lightweight, responsive, and standalone web tools to perform these calculations on the fly—designed to run seamlessly on a second monitor, laptop, tablet, or split-screen browser alongside your game.

---

## Available Tools

* **[Resonant Orbit Calculator](orbits/resonant-orbits.html):** Calculate the exact resonant orbit, carrier apoapsis, periapsis, and injection delta-v needed to deploy equidistant satellite constellations (e.g. for CommNet relays). Features an interactive, to-scale SVG orbit schematic, synchronous and minimum line-of-sight (LOS) presets, dive orbit support, and data for Stock KSP, Outer Planets Mod (OPM), Real Solar System (RSS), and Galileo's Planet Pack (GPP).
* **[Solar System Δv Map & Mission Planner](delta-v/map.html):** Interactive vector subway map and mission delta-V route planner based on community astrodynamics charts by Swashlebucky, s13g3, and Kowgan. Features interactive pan/zoom vector subway map with clickable station nodes and route highlighting, automated shortest-path mission routing between any two celestial bodies/orbits, aerobraking savings toggles, round-trip calculations, plane change buffers, safety margins, and step-by-step flight itineraries.

---

## Technical Architecture

* **Framework-Free & Zero-Build:** Built using clean, native client-side web technologies (HTML5, responsive CSS3, SVG/Canvas, and vanilla ES6+ JavaScript). Runs without Node.js, Webpack, Vite, or any build pipeline.
* **Fast & Self-Contained:** Runs entirely in any standard modern web browser with zero server overhead.
* **Local Execution:** Can be run locally by simply opening `index.html` in your web browser:
  ```bash
  git clone https://github.com/brantleyforrest/KSP-Tools.git
  cd KSP-Tools
  # Open index.html in any browser
  ```

---

## Credits & Attribution

* The **Resonant Orbit Calculator** is based on the original tool by **[Eric A. Meyer](https://meyerweb.com/)** ([meyerweb.com/eric/ksp/resonant-orbits/](https://meyerweb.com/eric/ksp/resonant-orbits/)), released under the MIT License.
* The **Kerbol System Δv Map** is based on the design by **/u/swashlebucky**, Kowgan, WAC, /u/CuriousMetaphor, /u/JellyCubes, and the "Lights-out" theme by **/u/s13g3**, licensed under CC BY-NC-SA 4.0.

---

## License

This project is licensed under the **GNU General Public License v3.0** (GPLv3). See the [LICENSE](LICENSE) file for the full license text.

Individual third-party components and algorithmic references retain their respective open-source licenses as noted in the [Credits & Attribution](#credits--attribution) section.
