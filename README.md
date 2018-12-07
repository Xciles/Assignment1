# Assignment 1
The previous developer of this application went on vacation before the customer was given a working application. 

You have been hired to fix his garbage and continue working on the application before the customer explodes with anger.

You have 4 tasks:

1. Start: 
* Split the files into its own classes
  * Use some seperation policy you find logical
* Add Additional rooms with navigation
  * Reuse existing functionality within the application.
* Let the player of the game choose and enter his own name
  * Assign the name if it is correct (for example to PlayerName)
  * If a player enter "" or " " ask the playername, keep asking for the player name until the player enters a proper name.

2. Extend the application
* Implement MoveToDirection
  * The method should set _currentRoom to the direction the player wants to navigate
  * Or the method should print some kind of error incase navigation is not possible
* Implement Additional commands
  * look -> Look arround 
  * exit -> Exit the game
  * help -> Show the help commands

3. Extend the application even more!
* Implement Monsters in some rooms
  * Monsters have HP and ATK points
  * There should be some (min 3) different monster types
* Implement the ability to attack the Monsters as the player.
  * This can use default ATK points for the player.
  * Gain EXP when the player kills a monster, and thereby increasing the ATK points the player has.

4. Extend the application even more even more!
* Implement the ability to pick up items dropped by monsters
* Implement a solution for the handling of commands
  * Currently this uses some kind of switch statement, find and use something else for this.
