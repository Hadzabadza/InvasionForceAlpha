# InvasionForceAlpha

-Movement overhaul: arrow keys set conditions, key release executes movement for code concision.
-Collision check: checks if a player has something in front of them.
-Player selection: click on a player you wish to move around.
-Extra tiles: fences, drop pod, roadmarks.
-Obstacles: solid, destructible, door.
-Door system: doors unlocked by default (Lock=0), to lock a door add 

	Lock="%locknumber%;

to its creation code. To give a key 

	global.Keys[%locknumber%]=true;

-Obstacle deletion: Players can clear destructibles in front of them by pressing X.
-Debug mode: press Space to switch. Displays obstacles and door locks.

