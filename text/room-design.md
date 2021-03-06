#Summary

Each ship will have a base set of rooms.
These rooms will fulfill a specific ship function and some can depend on others.
Having the room accommodated by crew will increase the ability of the room's function.
Without power the room will not function.
Ship types can have special rooms which play on the strength of that [ship's type](Ship-Type).

#Room Types

##Support Modules

Type           |   Crew    |   Function
---------------|-----------|----------------
Cockpit        | 1..3      | Control of tier 1 Movement, Offensive, Defensive and Support Modules.  
Bridge         | 4..14     | Control of up to tier 2 Movement, Offensive, Defensive and Support Modules.  
Command Center | 15..30    | Control of up to tier 3 Movement, Offensive, Defensive and Support Modules.  
Engine Level 1 | 1         | Allows base speed level.
Engine level 2 | 2         | Increased speed level.
Engine Level 3 | 3         | Further increased speed level.
Reactor Level 1| 1         | Base level of power to activated systems. 
Reactor Level 2| 3         | Increased level of power to activated systems.
Reactor Level 3| 9         | Further increased level of power to activated systems.
Sensors Level 1| 1         | Communications to objects outside ship.
Sensors Level 2| 1         | Communications to objects outside ship & scanning.
Sensors Level 3| 1         | Communications to objects outside ship, scanning & detection.
