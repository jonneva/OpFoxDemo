/-----------------------------------------------------------------------------/
Operation Fox Playable Demo - Copyright (C) 2015 Jonne Valola aka Jonnection
release 001
9.6.2015
/-----------------------------------------------------------------------------/


0. INSTALLING THE GAME ON GAMEBUINO
-----------------------------------

Copy OPFOXDE.HEX and EP1.DAT to your Gamebuino SD card. Use the Gamebuino loader
to load the game. 

(Experienced users can use AVRDUDE to flash the HEX directly) 


1. STORY
--------

Colombia 1982

Evil Drug Lord Sanchez has taken hostages to protect him against the C.I.A.
President Ronnie will not negociate with terrorists. The task of freeing the
hostages is handed to Major Willard Fox III, a hard-hitting Special Operative.

Major Fox has landed close to a village near Sanchez Camp. His task is to free
at least 20 of the hostages held in the village. Unfortunately the village
is hit by a torrential jungle rain at the middle of the mission.


2. CONTROLS
-----------

Left/ Right - Scroll left & right - SCROLLING DISTANCE IS LIMITED !
A Button	- Fire machine gun
B Button	- Grenades (NOT INCLUDED IN DEMO)
C Button	- Pause 

3. GAMESCREEN HUD
-----------------

Top left - Grenades (Not available in demo)
Top right - Number of saved hostages / goal to save
Bottom left - Ammunition clips
Bottom right - Health


4. CONTRAST & VOLUME CONTROLS - PAUSE MODE
------------------------------------------

While in "PAUSED" mode:

Left/ Right - Volume Level (0,1,2)
Up  / Down	- Contrast 
C Button 	- Resume Game
A + B		- Load Gamebuino Loader


5. EXIT GAME ( = LOAD GAMEBUINO LOADER, IF PRESENT)
---------------------------------------------------

either:
- press A + B when in PAUSED mode
- press and hold C, then press RESET, then release C after 1 second


6. GAMEPLAY TIPS
----------------

- shoot the thugs holding the hostages to free them
- hostages are not free immediately, they have to scroll to a safe distance
- game gets harder as it progresses
- this game is hard
- on purpose
- you get bonus health for shooting baddies
- remember to pick up all medikits and clips to get health and ammo
- instead of fighting every Jeep, try to scroll away if you can
- Jeeps and baddies that are close to the screen will hit you very hard. Be aware.


7. MUSIC AND LICENSES
---------------------

Game Code, Concept + Art
Copyright (C) 2015 Jonne Valola aka Jonnection
All rights reserved, NO WARRANTY
http://jonnev5.wix.com/rboygames
 
Music:

"Volatile Reaction"
Kevin MacLeod (incompetech.com)
Licensed under Creative Commons: By Attribution 3.0
http://creativecommons.org/licenses/by/3.0/

Uses PetitFATFS library

/*----------------------------------------------------------------------------/
/  Petit FatFs - FAT file system module  R0.03                  (C)ChaN, 2014
/-----------------------------------------------------------------------------/
/ Petit FatFs module is a generic FAT file system module for small embedded
/ systems. This is a free software that opened for education, research and
/ commercial developments under license policy of following trems.
/
/  Copyright (C) 2014, ChaN, all right reserved.
/
/ * The Petit FatFs module is a free software and there is NO WARRANTY.
/ * No restriction on use. You can use, modify and redistribute it for
/   personal, non-profit or commercial products UNDER YOUR RESPONSIBILITY.
/ * Redistributions of source code must retain the above copyright notice.
/
/-----------------------------------------------------------------------------/

