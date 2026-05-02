# DnD Damage Calculator

A simple web tool for Dungeon Masters to calculate damage during D&D 5e sessions. Select a monster from the D&D 5e API, view its stats, and calculate damage accounting for resistances, immunities, and vulnerabilities.

## Features

- Monster selector populated from D&D 5e API
- Display monster stats (AC, HP, CR, damage resistances/immunities/vulnerabilities)
- Damage calculator that applies monster's damage modifiers
- Clean, responsive UI using Tailwind CSS
- No JavaScript frameworks - pure vanilla JS

## Usage

1. Open `index.html` in a web browser
2. Select a monster from the dropdown
3. Enter damage amount and type
4. Click "Calculate Damage" to see the result with modifiers applied

## API

Uses the [D&D 5e API](https://www.dnd5eapi.co/) for monster data.
