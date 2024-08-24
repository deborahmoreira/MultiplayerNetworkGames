# Multiplayer Network Games
## GAME DESIGN DOCUMENT

**APRIL 2024 | Deborah Victória Lima Moreira**

---

### GAME TITLE
**ASTROBLAST** - A multiplayer game where astronauts battle in space.

### GAME CONCEPT

#### Setting
An arena in a grid format where some blocks are fixed and others can be destroyed.

#### Objective
The main objective is to be the last player standing by exploring a maze, using bombs to create paths, and defeating opponents.

#### How to Play
The player controls a character that must move through a maze, place bombs to destroy obstacles, and defeat enemies. They connect to the server, wait for other players, and the match begins.

### GAME MECHANICS
- Each player starts with a bomb and a unique power-up.
  - **Bomb:** Breaks 3 obstacles horizontally and 3 vertically.
  - **Power-ups:** 4 available:
    - **Kick and Punch:** The bomb travels to the next fixed block in a direction.
    - **Speed Bonus.**
    - **Dash:** Super speed in a single direction.
- Players can move in 4 directions on the grid (up, down, left, right). They start with few free squares to move and, as they place bombs, they free blocked blocks, which may hit nearby players or reveal extra bombs or bomb modifiers.
  - **Bomb Modifier:** Ship that jumps over the bomb that exploded nearby.
- Each game has a time limit, and as the time runs out, the arena shrinks, defeating the player if they are on the edge.

### VISUAL STYLE AND ART
Pixelated style with a futuristic, space, universe, and astronaut theme.

### PLAYER EXPERIENCE
Players need to act quickly and strategically to avoid being hit. The ranking system and online tournaments encourage ongoing competition and skill development.

### PLATFORMS AND TECHNOLOGIES
- Unity and C#.
