# Unity-DeepSpaceD6
An implementation of the board game Deep Space D-6 in Unity2D.

This is an implementation for personal use, credit to the board game designer: Tony Go.

To play (only applicable for windows), simply download the zip file, extract, and run the file named "Deep Space".


Game Instructions:

This game is played in rounds. In each round are the following phases:


1. Draw threat card.

	-Click on the threat deck (top left corner) to draw a card.
	
	-Drawn card will preview and then go to it's right place; outer threats will display on the right of the ship, inner threats on the left.
	
		The number in the top left corner of a threat card is it's health.


2. Roll threat die.

	-Click on threat die to roll (on the top-right, marked in red).
	
	-Outer enemies will be activated if one of their invokation numbers was rolled.


3. Roll crew dice.

	-Roll your current number of crew dice by clicking on the crew button (top right corner, marked in blue).
	
	-The number of dice rolled is displayed in the Returned section in the buttom-left.
	
	-Rolled crew icons will be displayed on the roll button, and the counters in the buttom right will increase accordingly.
	
	-Inner enemies will be activated if one of their invokation numbers was rolled by the threat die in the previous phase.


4. Use crew dice.

	-Use your available crew by clicking their respective buttons in the buttom right corner.
	
	-First, Scanner (gray) crew must be locked. You will see locked scanners on the top of the ship.
	
		When there are three Scanners locked, another threat card will be drawn automatically.
		
		A locked Scanner is not rolled in the next round and can be Returned by using a Medical crew member.
		
	-Medical (dark purple) crew can be used to either Return one Scanner, or to Return all crew in the Infirmary.
	
		Crew in the infirmaty will not be rolled in the next round.
		
	-Science (green) crew can be used to fully replenish ship's Shields (indicated in green in the ship's top left).
	
	-Enginner (orange) crew will replenish ship's hull (indicated in gray in the ship's top left).
	
		First one used will replenish 1 Hull, any additional will replenish 2.
		
	-Tactical (red) crew is used for attacking enemies. Only outer enemies with health can be attacked.
	
		First one will cause 1 damage to an enemy, any additional one will cause 2 damage.
		
	-Commander (light purple) crew can be used to turn other crew to any member.
	

5. End your turn.

	-Click "End Turn" button at the top center to end your turn.
	
	-Any dice that are not in the Infirmary and not a locked Scanner will be added to the Returned and will be rolled in the next round.
	

6. At any time you can click Esc to pause the game, and view the pause menu. From this menu you may quit the game.

Have Fun!





Special thanks:

-Tony Go for creating the game.

-Ben Braiman for making sprites for the ship's areas.
