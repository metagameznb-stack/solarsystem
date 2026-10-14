# Solar System — Educational 3D Model

A self-contained, browser-based 3D model of the Solar System built with plain
HTML5 canvas and JavaScript (no frameworks, no build step).

Everything runs in a single `index.html`. Just open it in a browser.

## What's inside
- **15 bodies** with real data: the Sun, 8 planets, and 5 dwarf planets
  (Pluto, Ceres, Eris, Haumea, Makemake), plus Halley's Comet.
- **Every moon** with data: Earth's Moon, Mars' Phobos/Deimos, the 4 Galilean
  moons, Saturn's Titan/Enceladus/Rhea/Dione, Uranus' Titania/Oberon/Miranda/Ariel,
  Neptune's Triton/Nerida, Pluto's Charon + 4 small moons.
- **Real orbital mechanics** — J2000 classical orbital elements from NASA's NSSDC
  factsheets, solved with a Kepler solver (Newton-Raphson) for true elliptical
  orbits with correct eccentricity and inclination.
- **3D rings** on Saturn, Uranus, and Neptune at their true axial tilts.
- **Particle effects** — animated solar wind, asteroid belt, Kuiper belt, and a
  streaming comet tail that always points away from the Sun.

## Controls
- **Drag** to orbit the camera
- **Scroll / pinch** to zoom (in or way out)
- **Click a planet** in the Objects list on the right to fly the camera in and follow it
- **Double-click** a body to focus it
- **Speed slider** runs from 1 day/s up to thousands of years/s
- Toggle orbits, labels, rings, belts, and solar wind; or **Fit Sun** / **Today**

## Data sources
NASA NSSDC Planetary Fact Sheets (nssdc.gsfc.nasa.gov), IAU/J2000 orbital
elements, and mission data (New Horizons, Dawn, Cassini, Rosetta, Juno).

## Live (GitHub Pages)
<https://zaibatsu.github.io/solarsystem/>
