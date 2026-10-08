# Antopia: Trail Finder

A browser-based educational game that introduces 8th graders to AI routing through Ant Colony Optimization (ACO).

## Core Idea

Find a low-cost route from the anthill to the real strawberry, then release batches of ants and watch the colony explore. Pheromone trails reinforce successful routes, while evaporation helps old trails fade. Compare your route with the colony’s results and see how many simple agents can work together to find better paths.

A cybersecurity challenge adds a rogue ant, fake scent, and a fake destination to illustrate sinkhole attacks and the importance of trusted route information.

## Features

- Interactive trail network with route costs, exploration, and hints
- Adjustable ant batches and pheromone evaporation
- Stars, badges, and short learning checks
- Cyber defenses such as trusted scent and blocking suspicious trails
- Optional sound and read-aloud narration
- Local session storage and CSV/JSON results export for teachers

## Tech Stack

HTML, inline CSS, and vanilla JavaScript in one HTML file. The map and characters use SVG. Browser APIs provide local storage, audio, and speech synthesis. Google Fonts supplies optional web fonts, with fallback fonts available.

## Run the Game

1. Download the game’s HTML file.
2. Open it in a modern web browser.
3. Complete the warm-up questions and start the challenge.

No installation, terminal commands, or build step required.

## Learning and Privacy Notes

Quiz responses and gameplay events are stored in the current browser, including the name, age, and grade entered at the start. Teachers should follow classroom privacy requirements when collecting or exporting results.
