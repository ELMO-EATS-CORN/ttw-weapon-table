# TTW Weapon Table

A static, single-file HTML table of weapon stats from a Tale of Two Wastelands
(TTW) install, with a critical-hit calculator and a head-to-head comparison of
any two weapons.

**Live page:** https://elmo-eats-corn.github.io/ttw-weapon-table/

## Features
- 546 weapon records, sortable columns, live search (`AND` / `OR` supported)
- Filters for skill, source file, availability (player / companion / AI / cut), Crit x >= 1.5
- Crit chance calculator: base chance x weapon multiplier, capped at 100%
- Compare any two weapons stat by stat
- Download the current view as CSV

## Data
- Extracted from a TTW install (TTW version 3.4).
- Values may differ with other TTW versions or mods.
- Only derived stats are included here, no game files or assets.

## AI disclosure
The HTML, table and crit calculator were generated with Mistral AI from a dump
of my TTW data, then reviewed and edited with Claude (Anthropic). The crit
formula was checked against community wiki documentation. Individual values
were not verified one by one in-game, so treat them as a reference.

## Status
Not actively maintained. Issues and pull requests may go unanswered.

## Disclaimer
Fan project, not affiliated with Bethesda, Microsoft or the TTW team.
Game data belongs to its respective owners.
