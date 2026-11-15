# Space Construction

A browser game for the NASA Space Apps Challenge 2026 (Space Mission Design Game). Players design a mission under a budget, make decisions during the flight, and see in a final report how their choices changed the outcome. Everything in the game is a fictional simulation inspired by real NASA missions. Credits, prices, fuel, energy, safety margin and gameplay timing are invented game rules.

## Play

Open `index.html` in any modern browser. No installation, server or internet connection is needed to play. The NASA source links inside the game open in a new tab and need internet.

## Missions

**Mission 1: BRAZIOSIRIS-REx, Bennu Sample Return.** Inspired by NASA's OSIRIS-REx. Equip a probe with 100 credits, send the GO command from Earth, and decide when to back away from asteroid Bennu. The laboratory report shows how equipment, fuel and timing decide whether a sample reaches Earth.

**Mission 2: Lunar Hedgehog, Helium-3 Survey.** A fictional crewed lunar expedition inspired by Artemis II and Apollo. Choose up to three parts within a budget and a payload limit, manage fuel, energy and safety margin through six phases, store flyby observations during a communications blackout, and decide whether to land and bring back a sealed sample for laboratory confirmation.

## NASA data used

Each mission shows its NASA evidence and its game assumptions on screen, with links. The main sources are:

- NASA, Design and Develop Science Missions (launch, space, ground and user segments).
- OSIRIS-REx pages on the sampling event at Bennu, the 18.5-minute signal delay, the 70.3 g and 121.6 g sample masses, the launch and the mission cost.
- Artemis II launch update, Flight Day 6 lunar flyby blog and press kit, Orion crew systems, Human Landing Systems, Apollo 11 mission overview.
- NASA Technical Reports Server, Concentrations of Volatiles in the Lunar Regolith, table 1 (helium-3 in Apollo soils, 4.2 plus or minus 3.4 ng/g).

## Technical notes

A single HTML file with plain JavaScript and canvas pixel art. No external libraries, fonts or images are loaded. The character sprites and sounds are generated inside the file.

## AI assistance

Anthropic Claude helped write and debug the code. OpenAI ChatGPT helped with the Mission 2 design specification, source checking and documentation. The team chose the mission themes, tested the game and decided the rules.
