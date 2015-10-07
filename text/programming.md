# Programming

## Breakdown 

The so called "game engine".
The following list is taken from Wikipedia.

- Physics – the programming of the game engine, including simulating physics, collision, object movement, etc.;
- AI – producing computer agents using game AI techniques, such as scripting, planning, rule-based decisions, etc.
- Graphics – the managing of graphical content utilization and memory considerations; the production of graphics engine, integration of models, textures to work along the physics engine.
- Sound – integration of music, speech, effect sounds into the proper locations and times.
- Gameplay – implementation of various games rules and features (sometimes called a generalist);
- Scripting – development and maintenance of high-level command system for various in-game tasks, such as AI, level editor triggers, etc.
- UI – production of user interface elements, like option menus, HUDs, help and feedback systems, etc.
- Input processing – processing and compatibility correlation of various input devices, such as keyboard, mouse, gamepad, etc.
- Network communications – the managing of data inputs and outputs for local and internet game play.
- Game tools – the production of tools to accompany the development of the game, especially for designers and scripters.

Re-grouping the above list we have

- Behind the scenes
  - Mechanics: the physics, rules, (potential) networking.
  - AI: code for adding independent agents, which still obey the game mechanics.

- Presentation
  - Graphics
  - Sound
  - User interface

There is also a third group for developing the original game and extensions.

- Development interfaces
  - Programming interface
  - Utilities: Level creator, etc.

## Approach

To preserve and focus the limited resource, reuse any readily available components.

# Candidates

Engine     | Core language | Extensions language
-----------|---------------|---------------------
Spring RTS |               |
Blender    |               |
Torque 3d  |               |
Panda 3d   |               |
Ogre       |               |
id Tech 4  |               |
