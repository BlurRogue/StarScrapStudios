# StarScrapStudios

GAME GOALS:
-"Polish our tutorial & create two new polished levels"
	-Two more puzzle variants.
	-Included textures.
	-Immersive Audio.
	-Simplistic AI behavior.

GAME GOALS EVALUATION:
-Tutorial Level is polished
-Game includes two new levels
	-New levels feature new content.
-Game has _____ new puzzles.
	-PUZZLE STAND
		-A quick time event where the player must put in inputs according to the criteria before the time runs out. Must succeed 3 times.
		-Found in Level 1.
	-TRIPLE KEY LOCK
		-A puzzle where the player must find and locate 3 or more keys in order to unlock.
		-Found in Level 0.
	-ACCESS CONTROL PANEL
		-A puzzle where ______.
		-Found in Level 2.
	-CODE SEQUENCER
		-A puzzle where ______.
		-Found in Level 2.
	-BOSS SEQUENCE
		-A puzzle where ______.
		-Found in Level 2.
-Game has newly made textures and assets.
	-Walls, Doors have new materials
	-Clues, such as ID CARDS, NOTE, and CHILD DRAWING, have narrative textures
	-Vending machine textures.
	-New locker and puzzle textures as needed.
-Game has immersive audio.
	-Interaction sounds added to game.
	-Level 0 audio.
	-Bruin attack sequence audio. 
	-Other.
-Simplistic AI behavior
	-Bruin exists within game.
	-Bruin will chase the player, try to attack.

PROJECT DESCRIPTION:
-Quoted from Jira.
	-"While our original goal from last semester has changed due to initial over-scoping and adjustments to our team structure, our overall vision for Teddy & Co. is to present three uniform and polished levels that seek to immerse the player through the environment, audio, and narrative. Our game is first and foremost a puzzle game, and so we’d like to feature at least 5 unique puzzle variants (2-3 per level). Our ambitions from our previous semester still remain strong though, and for that reason, we’d like to feature Bruin, our game’s boss that stalks you, at least once within these levels - whether that’s a cheap scare or some simplistic AI."

PROJECT DESCRIPTION EVALUATION:
-Game has 3 uniform and polished levels. 
-Game is immersive.
-Game is a puzzle game. Game has over 5 unique puzzle variants. Many different puzzles. 
-Game features Bruin. Bruin chases player. 


GAME CONTROLS
- Interact: E
	Triggers the associated INTERACT event of the object. 
- Fire: RIGHT MOUSE CLICK
	Fires a projectile if you are holding a weapon.
- Jump: Space Bar
	Launches the player into the air if you are not falling
- Flashlight: Q
	Toggles a small local flashlight.
- Escape: ESCAPE
	Exits out of an interface when otherwise focusing, such as on a Puzzle or Inspection.
- Puzzle Navigation: UP, DOWN, LEFT, RIGHT
	When focused on a puzzle, press these keys in order to trigger events or move around objects on the puzzle
- Switch Interaction Mode: TAB
	Used to toggle between interaction modes.
- Exit Editor: F1



GAME STATE CONTROLS AND ADVICE
-Inspecting: 
	Occurs when interacting with certain items, like ID cards or clues.
	Item will appear before you. You can move the item around and zoom in and out. 
	CONTROLS:
	- Move item: HOLD LEFT MOUSE & MOVE MOUSE
	- Scroll item: SCROLL WHEEL
	- Escape/Close out: ESCAPE
	TIPS:
	Flip an item by using Mouse Y
	Rotate an item by using Mouse X

-Locker Puzzle Interface:
	Occurs when interacting with locker puzzle.
	Will focus on the locker's digits more closely. 
	CONTROLS:
	-Switch between digit: LEFT, RIGHT
	-Turn digit: UP, DOWN

-Grandfather Clock Puzzle Interface
	Occurs when interacting with Grandfather Clock puzzle.
	Will focus on the Clock's hands more closely.
	CONTROLS:
	-Switch between hands: UP, DOWN
	-Turn Clock Hands: LEFT, RIGHT
	TIPS:
	-Spamming inputs can cancel rotation events. 
	-For best consistency, rely on counting rotations rather than visuals. For reasons why, see above.

-Wire Puzzle:
	Occurs when interacting with Wire Puzzle puzzle on Level 0.
	In order to work properly, player must Switch Interaction mode by pressing TAB. 
	Once finished, player should return to previous interaction mode, by pressing TAB again. 
	CONTROLS:
	Press "E" to rotate wire blocks.
	The red and green wires need to be connected to the purple wire. 
	TIPS:
	The player can change the line by rotating each block. 
	After the connection, the door opens.

-Hieroglyphics Puzzle:
	Occurs when player enter Final area.
	Select the correct four Hieroglyphics from a set of eight.
	Step on the 4 correct answers,Nuclear battery shields open.
	TIPS:
	Require the player to find specific angles to reveal them.


-Puzzle Stand
	Occurs when interacting with the Puzzle Stand puzzle.
	Will focus on the puzzle and hallway before them.
	CONTROLS:
	-Enter WASD input: UP, LEFT, DOWN, RIGHT
	TIPS:
	-Player can be timed out, and restart current puzzle state, so be quick to enter in your inputs.
	-Player is being chased by Bruin, so be quick to enter in your inputs.
	-Arrow Key bindings are similar to WASD bindings. Place left hand on Arrow Keys and press the same arrow key that would be associated with that same WASD input. 

GAMEPLAY WALKTHROUGH
---WARNING---
---WALKTHROUGH WILL CONTAIN SOLUTIONS TO PUZZLES---

///LEVEL 0///

LEVEL 0//ROOM 0:
-Player spawns in Spaceship
-Walk forward
-Press E to open Spaceship door
-Walk forward
-Press E to open Spacestation Door

LEVEL 0//ROOM 1:
-Player is in Observation deck
-Observe the nebula outside and ponder it's beauty
-Walk forward until reaching door
-Press E to open Door to ROOM2

LEVEL 0//ROOM 2:
-Player is in Waiting Room.
-Walk forward & press E. Door is locked.
-Walk into small cubicle to your right.
-Notice the locker. Do not know code.
-Walk to the only unexplored door in the room. Press E to interact.

LEVEL 0//ROOM 3:
-Player is in Small Break Room.
-Walk towards vending machines.
-Pick up card on floor, slightly beneath table, close to vending machines by pressing E.
-Player is inspecting. Flip card over, rotate to read properly. Player notes numbers: 8-3-4, ?-?-?, 3-6-9
-Press ESCAPE to exit.
-Exit room to reenter ROOM 2.

LEVEL 0//ROOM 2:
-Player is in Waiting Room.
-Player can unlock Locked Door by pressing E (uses ID card as key).
-Player can unlock Locker on floor in small cubicle.
	- Enter in following code [8-3-4]
	- Pick up ANIMAL PLUSH - BEAR.
-Leave room to enter ROOM 4

LEVEL 0//ROOM 4:
-Player is in Main Hall.
-Player notes the new ambience of the room.
-Player notes giant statue of Bruin [Bear Mascot] before them. 
-Player walks around statue, and notices CHILD DRAWING
-Player presses E to interact. Inspects item. Player notes 3 ANIMAL PLUSHES.
-Player walks into Dining Area, left of door used to enter room.
-Player notes Grandfather Clock.
-Player walks towards seating area. Picks up SMALL NOTE on first cubicle on the grandfather clock side on further seat. 
-Player presses E to interact. Inspects item. Player notes code [9h 30min]
-Player walks to Grandfather Clock. 
	- Presses E to interact. 
	- Enters code [9h 30min] by spinning LARGE HAND 9 times, and spinning SMALL HAND 6 times.
	- Pick up ANIMAL PLUSH - BUNNY
-Player walks to other side of room. Notes locked door and wire puzzle. 
[PAN ENTER INSTRUCTION HERE]

LEVEL 0//ROOM 5:
-Player is in Storage Room.
-Player walks to end of room. Notes small locker on left-hand side.
-Player remembers previous code. 
	- Enters [3-6-9] into Locker.
	- Pick up ANIMAL PLUSH - CHICKEN
-Player returns to Main Hall. 

LEVEL 0//ROOM 4:
-Player is in Main Hall.
-Player walks to giant statue of Bruin [Bear Mascot].
-Player presses E to interact. Player has unlocked door behind Bruin.
-Player walks past Bruin. Interacts with door.
-Player begins LEVEL 1.

///LEVEL 1///

LEVEL 1//ROOM 0:
-Player is in Museum Walkway. 
-Player walks to door in front of them. Turns left.
-Player walks to end of hall. Notes door is locked.
-Player walks to other end of hall. Opens door.

LEVEL 1//ROOM 1:
-Player locates ID CARD on left hand side table. Presses E to interact. Inspects item.
-Player exits room.

LEVEL 1//ROOM 0:
-Player is in Museum Walkway. 
-Player walks to other end of hall. Feels shiver down their spine. Player prepares for QUICK TIME EVENT.
-Player unlocks door with ID CARD. Notes PUZZLE STAND before them.

LEVEL 1//ROOM 2:
-Player walks around to PUZZLE STAND. Player notices giant bear mascot chasing them down from the hall they were just in. Presses E to interact with PUZZLE STAND.
	TIP: If pressing E here does not trigger anything, try pressing UP or DOWN and then trying again. Player could also leave and reenter collision to fix.
-Player is in QUICK TIME EVENT.
	-Player must enter in exact code sequence in order to override the door in front of them and prevent Bruin from ending them!!!!!!!!
	-Player must succeed 3 times in order to override door.
-Player is relieved to be alive.
-Player spins around and interacts with newly unlocked door.
	-Door is elevator.

LEVEL 1//ROOM 3:
-Player is in Toy Testing Facility.
-Player is locked room. Must escape.
-Player walks to Shooting Range. Notices WEAPON. Presses E to interact.
	-Player now has TOY WEAPON.
	-Player can now press RIGHT MOUSE BUTTON to fire toy projectile.
-Player shoots center target of Shooting Range.
	-Player enters Shooting Range.
	-Player looks behind center target.
	-Player notes code [9-1-6]
	-Player exits Shooting Range.
-Player walks around to Computer Bay. 
-Player notices LOCKER on floor.
	-Presses E to interact.
	-Player enters code [9-1-6]
	-Player picks up ID CARD.
-Player returns to other side of large room. Player walks to locked door. Presses E to interact.

LEVEL 1//ROOM 4:
-Player is in Unnamed Hallway.
-Player walks to end of Hallway. Sees door. Presses E to interact.

LEVEL 1//ROOM 5:
-Player is in Connecting Room.
-Player notes two locked doors.
-Player walks to unlocked door. Presses E to interact. 

LEVEL 1//ROOM 6:
-Player is in Monitoring Room.
-Player notices code left behind on Computer Monitor. Player notes code [5-7-2]
-Player notices Locker in back corner of room.
	-Presses E to interact.
	-Enters code [5-7-2]
	-Picks up ID CARD.
-Player exits room. 

LEVEL 1//ROOM 5:
-Player is in Connecting Room.
-Player tries both locked doors. One door unlocks. Player enters room.

LEVEL 1//ROOM 7:
-Player is in Electrical Room.
-Player notices ACCESS CONTROL PANEL. 
	-Presses E to interact.
-Player exits room. 

LEVEL 1//ROOM 5:
-Player is in Connecting Room.
-Player uses ACCESS CONTROL PANEL on last locked door. Door unlocks.

LEVEL 1//ROOM 8:
-Player is in Observation Room.
-Player exits room through next door. 

LEVEL 1//ROOM 9:
-Player is in Unnamed Hallway.
-Player follows hallway until door.
	- Presses E to interact. 
	- Player begins LEVEL 2. 

///LEVEL 2///Corridor
-Player is in Hallway to final Room.
-Bruin starts to chase player.
-Player interact control panel at the end of Hallway.
-Wait for the door to final Room open.

///LEVEL 2///Final Room
-Player is in Final Room.
-Player Solve Hieroglyphics Puzzle.
-Player get nuclear battery, Bruin came in the Room.
-Engage Boss Fight




