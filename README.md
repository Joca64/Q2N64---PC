# Q2N64 -> PC
The first planet (4 maps) from the Nintendo 64 version of Quake 2 ported to PC

THIS IS A COPY OF THE README FILE INCLUDED IN THE ZIP DISTRIBUTION:

===================================================================================
September 9, 2016
===================================================================================

Title                   : Quake 2 N64 -> PC
Filename                : q2n64.pak   
Author                  : Joca64
Email Address           : feverishtoast@gmail.com
Twitter:		: @Joca64
Date of release		: September 9, 2016
Description		: Port of the first planet (4 maps) from the Nintendo 64 version of Quake 2.
				
Additional Credits to:	id for the original game.
			Raster Productions for the Nintendo 64 version.
			Mark Shan for the kmquake2 sourceport.
			

=========================================================================================

* Play Information *

Game			: Quake II v.3.20, tested mainly with kmQuake2 
Level Names      	: Strogg Outpost, Central Complex, Intelligence Center, Communications Center
File Names		: e1m1.bsp, e1m2.bsp, e1m3.bsp, e1m4.bsp
Single Player           : Yes.
Cooperative 		: Yes. (4 coop starts on each map, but have not been tested)
Deathmatch 2-8 Players  : No.
Difficulty Settings     : Yes. (easy, medium and hard are identical to the originals)
New graphics		: No.
Anything else new:	: No.

* Construction *

Base            : Maps built from scratch using the original N64 versions as visual reference.
Build Time      : 4 full days per map, on average.
Editors used    : QuArK 6.6 Beta 6
		   	  

Compilation:	TxQbsp
		Qvis3
		Arghrad

		
============================================================================================
Known Bugs      : Lighting is a bit messed up on the rocky areas in map 2 and 4, causing
		  weird shadows.


* Differences from the original N64 version*

The only new content in this pak are the maps, there are no new items or textures. This means
that this is not a 100% faithful experience to the N64 version, however it is pretty close.

E1M1 -	The starting room is a bit uglier than it should be.
	PC Quake 2 has no invisibility power up, it was replaced by the power shield.
E1M2 -	Explosive charge item doesnt exist, was replaced with the Airstrike marker.
E1M3 -	Nothing of note.
E1M4 -	Nothing of note.

Scrolling textures are much less versatile in the PC version, these were not included.
All custom textures from the N64 version were replaced by the closest match from the default
PC textures. None of the level intermission screens were included.
The console rendition of the game does not have an inventory, so if you want the closest
experience, activate every item as soon as you pick them up x)
Obviously I cant distribute the original OST, but if you do own it, the track numbers used are
the ones listed here: https://aubreyhodges.bandcamp.com/album/quake-2-nintendo-64-official-soundtrack
Either use a CD or replace the music files in your sourceport.


--------------------------------------------------------------
Background:
--------------------------------------------------------------
This past month of August, I was feeling like replaying the Nintendo 64 version of Quake 2, mainly
because I couldn't remember any of the game's maps apart from them being completely different
from the PC version. Alas, after getting my console from storage and setting it up, I found out
it died while in its sleep. Since the game doesn't seem to work very well on the emulators I tried it
with (items and enemies are seen through walls), I searched the web to find out if someone had done a PC
port of the game, similarly to the Doom 64 total conversion available. Since all I could uncover were
forum posts of people complaining that said mod was nowhere to be found I got frustrated.
Due to boredom, I started to recreate the big water room from the first map. After completing
it, I figured, "I'll just make the next room as well" until I ended up completely making the
first map from scratch. Again, struck by boredom, completed the second map, then the third and finally
just settled on completing the first planet from the game.
--------------------------------------------------------


* Loading information *

To load this Q2 pak on kmquake2:
- Get kmquake2 at: http://www.markshan.com/knightmare/
- Place "q2n64.pak" in your /quake2/baseq2/ directory.
- Start kmquake2 as you usual.
- Pull down console, type "skill #" (# = 0 through 4) to choose your difficulty. Press enter.
- Then type: "map e1m1" to begin.
(Do not type the quotation marks)

To load this Q2 pak on vanilla quake:
- Place "q2n64.pak" in /quake2/q2n64/ directory.
- Start Quake 2 with the +set game q2n64 parameter.
- Pull down console, type "skill #" (# = 0 through 4) to choose your difficulty. Press enter.
- Then type: "map e1m1" to begin.
(Do not type the quotation marks)
		 

* Copyright / Permissions *

You MAY distribute this PAK through any electronic network, provided you include this file 
and leave the levels in it's original form.

*Archive info*
Archive filename: q2n64.zip

---------
