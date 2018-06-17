# Code of Kutulu

## Statement mistakes
- Shelters start with 10 energy . [..] Shelters get refilled to 10 every 50 turns.
  => Shelters starts with 0 energy. [...] Shelters get refilled to 10 every multiple of 50 turns, except turn 0.

## Statement imprecision
- If a shelter is supposed to heal more than its energy for a turn (1 energy but two explorers for instance) everyone is healed and the shelter's energy is set to 0.
- PLAN and LIGHT are created by the explorer but they stay after the explorer's death until they fade out.
- Minions pick their new target AFTER explorers moves.
- The prefered direction URDL is offseted by 1 more each turn. Meaning turn a minion will preferer Up instead of Right at turn 0 but he preferers Right instead of Up at turn 1 (RDLU), and so on.

## Known bugs

- PLAN still healing after death of a player (doesn't affect the score)

# Other ressources

## Game design document
This is the first document we shared about the game
https://docs.google.com/document/d/1jQkYszU6UipM8QFGnKm3oSypcYnELiwpK0SM8uqgsfQ/edit?usp=sharing
