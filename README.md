# Bachman

A maze-chase game starring a hungry Havanese who gobbles **pigs in blankets** while four Olivias: Swiss Olivia (red), British Olivia (light blue), Aussie Olivia (yellow) and Scottish Olivia (dark blue), each with her flag on her jumper, hunt them round a holly hedge maze.

- Eat every pig in blanket (10 pts) to clear the level.
- Grab a **bone** (50 pts): for a few seconds the Olivias get scared and you can chase them; eaten ones float home as just their glasses (200, 400, 800, 1600).
- A **Christmas pudding** turns up twice a level for bonus points.
- Extra life at 10,000.
- While a bone is active, the dog barks as he eats. Change `BARK_CHOICE` in `index.html` to `"yap"`, `"arf"`, `"woof"` or `"retro"`.
- Background music: J. S. Bach, Prelude in C major, BWV 846, played quietly on a loop.

## Play

Open `index.html` in a browser. There is nothing to install or build.

- Arrow keys or WASD to move, Enter to start, P to pause, M to mute, B to switch the Bach music on or off.
- On a phone: tap the maze to start, then swipe or use the on-screen arrows. The Pause, Music and Sound buttons sit under the maze.
- On iPhone, sound follows the silent switch: flip it off to hear the barks and music.

Everything is drawn in code inside `index.html`: look for `drawDog`, `pigSprite`, `boneSprite` and `drawCat` (the chasers) to change the characters, and `MAZE` to redesign the level.
