# Game Design Document

## High Concept
* Gen 3 Pokemon game with access to all currently available mons and gimmicks
* Ideally balanced for both nuzlockes and casual play

## Design Pillars
* No engine forks unless absolutely necessary (RHH did the hard work for us)
* Prioritize team variety and the exploration piece of Pokemon
* Optionally reduce the grind (particularly for nulockes)

## Target Player Experience
* Intended to be the ROM for Ammar and I to finally do our soul link nuzlocke.
* Should be challenging under nuzlocke constraints but fair and fun to play casually (Logan)

## World & Progression
* No new areas planned beyond potential legendary/mythical warp zones.
* Progression should be vanilla to maximize encounter options and panic for nuzlockes

## Pokémon Availability & Encounters
* RHH's pokeemerald-expansion natively includes all mons through Gen 9 and many of their alternate forms (GMax, Megas, etc.)
* However, all mon placement is currently vanilla and these mons will need to be added.
* There are currently limitations on the engine around what we can and cannot add to each area/zone:
    * Land: 12 slots
    * Water: 5 slots
    * Fishing: 10 slots across all 3 rods
    * Rock Smash: 4 slots
* These slots can be expanded by changing the enginge's encounter code but that's out of scope for now.

## Battle Design & Difficulty
* The difficulty will likely come from the access to gimmicks. RHH's pokeemerald-expansion also tweaked the trainer AI to be smarter without a massive jump in difficulty.

## Trainers & Bosses
* Not intending to ADD new trainers to the game
* Trainers should use more than just Gen 1-3 pokemon
* Each gym should take advantage of at least 1 gimmick

## Items & Quality of Life
* Desire: Choice at the beginning of the game to enable "nuzlocke" mode
    * Gives the player:
        * 999 Rare candies
        * Disables exp gain from battles
        * Unlimited TM usage
        * 50 Pokeballs to start
        * Running shoes at the start?

## Story & Tone
* No planned deviation at this time

## Maps & Level Design
* No planned deviation at this time

## Technical Constraints & Engine Rules
* Currently favoring data driven changes (maps/tilesets/minor scripts etc.) over code changes
* Imposes limits on the pokemon slots as previously mentioned

## Development Phases
* (current) - Trialing tools and learning
* Wild Pokemon placement, google sheet here{TBD}
* Trainer adjustment, google sheet here{TBD}
* OnStart changes

## Testing & Balance Plan
* RHH's pokeemerald-expansion does contain a few debug tools to help us evaluate the game.
* Part of the fun will be playing through it a few times and seeing how it feels.
* Opening up to a small community for testing and comments would be ideal.

## Open Questions / Ideas
* None at this time.

## Notes
* Using PoryMap as the map / event editor at this time
    * Compiled by myself on Linux