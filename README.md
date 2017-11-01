*******************************

  _____          __          
 / ___/__  ___  / /________ _
/ /__/ _ \/ _ \/ __/ __/ _ `/
\___/\___/_//_/\__/_/  \_,_/ 
                             

******************************

-------
General
-------

- A 2d side-scroller clone of Contra (1988) game created using python and pygame library.


------------------
Build instructions
------------------

Dependencies : Python 3 . Pygame latest (1.9) 32-bit
	Pygame works with 32 bit version of Python only

	Install Python 3 and Pygame 1.9 from 
	Add python3 to PATH variables
	Go to the folder containing the game and run

	On Windows

.../Contra/>   python main.py

	On Linux

> python main.py
	
	On Mac

> python main.py

Note That the name of the program can be 'python' or 'python3' depending on whether you already have python preinstalled

-----------------
Game Instructions
-----------------

Controls
--------

A - Move Left
D - Move Right
S - Drop to a lower platform
SPACE - Jump
Left Mouse Button - Shoots in the direction determined by the mouse position
Right Mouse Button - Dash
Mouse Move - Direction of shooting

Notes :
Direction of shooting is determined by the mouse position. Mouse above the player shoots a bullet at an angle of 45 degrees 
from the ground
Below the player, -45 degrees wrt the ground
RMB activates Dash when it is out of cooldown
Its cooldown is depicted in top center of the screen
Use this ability to cross broken bridges

Rules
-----

* Get to the end of the Level and defeat the bot tanks
* You will die if you lose all your health
* Each bullet hit will decrease your Health by 1
* Hitting an enemy unit will INSIANTLY KILL you
* Running soldiers will be difficult to see underwater. (Only their head is visible )



Powerups
--------

F - Resets cooldown of Dash
B - +1 Health
Bird - (Powerdown). Causes the player to drop down if taken when on a platform

Notes:

----Jump, Right and Dash for longer distance
----Note that the bird powerup will trigger only if you are walking 
on a platform while activating.
----Hence jumping directly on top of the powerup will not activate as you are not on a platform. This can be
used to prevent unwanted drops to death
----Trying to drop when on water will cause you to drown and die !!

Additional Details about Mechanics
----------------------------------

A random powerup drops in front of the player every 2 seconds. If it goes out of screen behind the player, it disappears
Snipers shoot only when the player is infront of them
Soldiers who run across the screen are generated randomly every 3 seconds in front of the player
------------------------------------------------
All global settings are present in the 'settings.py'. They can be changed by the player to make the game more interesting and/or challenging
------------------------------------------------

Asset Credits
-------------

Background -- Zephiel87
Sound -- Jake Kaufman on ocremix.org BGM
      -- Sprite sound effects from bfxr.net
Sprites -- Searched on google images

 ____  _  _   __   __ _  __ _  _  _  __   _  _    ____  __  ____    ____  __     __   _  _  __  __ _   ___ 
(_  _)/ )( \ / _\ (  ( \(  / )( \/ )/  \ / )( \  (  __)/  \(  _ \  (  _ \(  )   / _\ ( \/ )(  )(  ( \ / __)
  )(  ) __ (/    \/    / )  (  )  /(  O )) \/ (   ) _)(  O ))   /   ) __// (_/\/    \ )  /  )( /    /( (_ \
 (__) \_)(_/\_/\_/\_)__)(__\_)(__/  \__/ \____/  (__)  \__/(__\_)  (__)  \____/\_/\_/(__/  (__)\_)__) \___/

***********************************************************************************************************



	
