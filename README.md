# Project Archipelago

**Genre:** 3D Survival / Analog Automation / Cozy Engineering

**Visual Style:** Low Poly / Voxel Art (high readability, "blocky" aesthetic with realistic lighting and water shaders)

**References:** Timberborn, Moonglow Bay, Voxel Tycoon, Unrailed

**Perspective:** Isometric with perspective (RTS Style)

**Mode:** Singleplayer & Co-op (up to 4 players)

**Engine:** Godot 4.6 (C# for critical systems + GDScript for gameplay)

## Overview

**Core Loop Summary:** Clear land, gather resources, build infrastructure, automate processes, explore new islands, survive, and discover.

**Camera System:** 3D Perspective (High-Angle / RTS Style) with an "X-Ray" / "Dither" system: Objects (trees, walls) obstructing the character become semi-transparent in a circle around the player.

---

## Detailed Core Loop

1.  **Survive:** Satisfy hunger and thirst through manual labor (carrying water, chopping trees).
2.  **Build:** Create a safe shelter and basic tools.
3.  **Automate:** Use physics and gravity to offload hard labor (irrigation systems, transport chutes).
4.  **Explore:** Invest saved time into building boats and launching expeditions to dangerous islands for unique resources and ancient knowledge.

---

## Gameplay Systems & Mechanics

### Physiology and Ecology
* **Needs:** Hunger, thirst, stamina, temperature (weather impact on the character).
* **Resources:** Every element (palm tree, stone) is interactive and destructible (Voxel).
* **Flora and Fauna:**
    * Animals have life cycles and react to day/night cycles.
    * **Genetics (Breeding):** Simple trait system (e.g., Productivity vs. Resilience). Possibility of cross-breeding species.

### Engineering and "Analog" Automation
A system based on physics, gravity, and kinetic energy rather than "magic conveyor belts."

* **Gravity Logistics:** Drop chutes (wood slides down hills), zipline systems, river log driving.
* **Transport:** Minecarts on rails (require momentum or propulsion), manual cranes.
* **Water:** Liquid physics (simplified, cellular). Digging canals, dams, sluices, water wheels.
* **Power Sources:**
    * **Muscle Power:** Player turns a winch/crank.
    * **Animals:** Draft oxen, horse whims/capstans.
    * **Elements:** Water (water wheels), Wind (windmills).

### Progression: "Learning by Doing"
* **Practice:** The more you dig, the less stamina you consume.
* **Discoveries:** Finding a new raw material (e.g., Sulfur) or a schematic (in a wreck) unlocks new recipes at the "Drafting Table."

### World and Exploration
* **Structure:** Archipelago of procedurally generated islands.
* **Ancient Mysteries:** Ruins, puzzles, environmental riddles, "forgotten knowledge" schematics.
* **Home Island:** A safe haven, starting with resources from the crash (rations, scrap), mild climate.
* **Hunting & Fishing:** Hunting wild animals, traps, fishing nets, rods, spears.
* **Expeditions:**
    * Construction of modular rafts and boats.
    * **Risk Biomes:**
        * **Volcanic Islands:** Mineral wealth (sulfur, obsidian), but high heat and lava hazards.
        * **Mangroves:** Difficult, swampy terrain, but unique herbs and rot-resistant wood.
* **Weather:** Dynamic systems. Downpours fill retention tanks (and create mud that slows down carts); droughts force water conservation.
