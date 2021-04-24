Title    : Rocket Arena 2
Filename : ra2250cl.exe
Version  : 2.50 Release
Date     : 4/17/99
Authors  : David 'crt' Wright <wrightd@gamespy.com>
           Mungo <bml@netwiz.net>
Web Page : http://www.planetquake.com/arena
Discussion list: rocketarena-subscribe@list.gamespy.com

Intro
-----
Welcome to Rocket Arena 2. You are about to play one of the most fun (and
most addictive) mods ever created for Quake 2. Please take a 
moment, however, to read this entire file. It contains important info
and answers many common questions.

Troubleshooting/FAQ
-------------------
Since most people will not read this whole file, this info is going at the top!
If you don't find an answer here PLEASE READ THE REST OF THE FILE!

1. I get a "map not found" error when connecting to the server.
A: Either the server is not running with the "arena" directory set, or your files
are not installed correctly. Quake 2 3.14 and above should set the game directory
automatically.

2. All the players have white boxes coming out of them.
A: You do not have the VWEP pak2.pak installed. Get it from the Rocket Arena 2
 downloads page. Install it in your quake2\baseq2\ directory.

3. The player's skins aren't showing up in pickup arenas, or I get a pic not found error.
A: The skins files either got overwritten, or were never installed in the first place.
 Try reinstalling by following the instructions below.

4. Is it cheating to give out the other team's health numbers to my teammates?
A: YES. YES it is. So don't do it. We left in the ability for observers to talk to
 players, so please don't abuse it. It was left in so that observers can cheer
 for their teammates and encourage them, not so they can help their teammates cheat.
 Giving out health numbers ruins the suspense and strategy of the game. So just don't do
 it. You wouldn't like your health given out, so don't give out other peoples'. End of 
 subject. This discussion is closed.

5. Is using the BFG Cheating?
A: This is a much tougher question, and I have devoted a short essay to it. You can find
 it at: http://www.planetquake.com/servers/arena/bfg.html
 However, the basic answer is: if the BFG is turned on, it is not cheating to use it.
 The BFG is off by default and can only be turned on by the server admin or by voting.
 Please don't annoy people by voting repeatedly to turn it on or off.

6. Is the Rocket Arena 2 source code available?
A: Not at the moment. It may be released at a later date, but not in the foreseeable future.
 If you have a mod and are interested in learning how something was done in RA2 feel free
 to contact one of the authors and we will get back to you (time permitting). 
 The menu source (although a slightly older version) has been released on the RA2 web page. 
 The current version may be released if we can clean it up and pry it away from arena.

7. How do I make a Rocket Arena 2 map?
A: The Rocket Arena 2 maps specs are avaiable for download on the Rocket Arena 2 page.

8. The Player Setup screen in multiplayer options crashes Quake 2.
A: You probably have old files lying around from the beta test. Delete your
\quake2\arena directory and reinstall only the release files.

9. I've got some menu or something, what do I do?
A: You read the rest of this file!

10. I get a "Local map version differs from server: 335323 != 323252"  Error.
A: Either your pak file, or the pak file on the server is corrupted. Try reinstalling.

Installation Instructions
-------------------------

If you are reading this file, you have probably already installed RA2, but please
read these instructions to make sure you did it correctly.

When you run the EXE you will be prompted for an install directory. Just
enter your correct Quake 2 directory when prompted.
That's it. It's installed. See below for how to connect to servers and play.

----
If you are unable to run the .EXE (on a Unix machine for example) you can
rename the file to .ZIP and follow these instructions.

To install: UNZIP the ZIP file into your QUAKE 2 directory, preserving directory
names. A quake2\arena directory will automatically be created. You can use
DOS PKUNZIP, UNIX unzip, or Windows PKZIP/WinZIP. It should look like this:

C:\QUAKE2> pkunzip -d c:\windows\desktop\????????.zip
or
$/usr/games/quake2> unzip -L /tmp/????????.zip

----

Playing Instructions
-------------------------

To connect to a Quake2 Arena server, use GameSpy (www.gamespy.com) with
the Rocket Arena 2 tab.

To install the Rocket Arena 2 tab:
1. Start GameSpy
2. Go to the VIEW menu and select CUSTOM TAB
3. Click IMPORT, and select the Q2ARENA.QST file in your \quake2\arena directory.

Select Quake 2 on the left.
Select the Q2 Arena Tab, go to File-Update This Source

Click, and play. Your game directory will be set to "arena" automatically.

If you get an error about a sound or map not being found, you installed the
pak incorrectly or did not set up GameSpy as above.

NOTE: Registered GameSpy Users can find Rocket Arena 2 servers faster using
SmartSpy. Just follow these instructions:
1. Start GameSpy
2. Right click on "Quake 2" on the left master list
3. Select "Add SmartSpy List" from the right click menu
4. Type "Rocket Arena 2" in the name field
5. Type "arena" (no quotes) in the Game Type field
A new "master" will be added under Quake 2. Just right click and hit update!

You can also connect to a server manually by running:
quake2.exe +connect server.ip.address
The +set game arena is set automatically by Quake 2.

To run a server you must download the SEPARATE server files.
This applies even if you just want to run a listen server on your LAN at home.

Game Overview
-------------
Rocket Arena matches are played in "arenas." Each map may have one or more arenas
in it. When you connect to a server, you need to either create or join a team, and
then enter an arena (if the team isn't already in one).
Once you are in the arena you will be put in line to fight. See below for 
more specific instructions.

Navigating the Menus
--------------------
The menus are controlled by the same keys you use to do your inventory.
(words in quotes are console commands, words in parentheses are the default
key bindings)

"invprev" and "invnext" ([ and ]) go up and down on the menu

"invuse" (ENTER) selects an item

"inven" (TAB) toggles a menu on/off. If a menu does not show up when you think
it should, try hitting TAB a few times. Also, if you are in an arena and
want to leave, hit TAB to bring up the observer menu.

"invdrop" (', same key as ") decreases values on the Admin and Voting menus
"invdrop" is also used on the Arena Selection menu to go directly into
Observer Only mode.

How to Play
-----------

When you first join a server you will probably see a message of the day window.
READ THE INFO, and then hit Enter (invuse) to clear it.

You will then be asked to either join a team or
create a new one. The number after the team name is the number of players on the team.

If you want to play by yourself, or start a team, then select
'Create Team'

If another player has asked you to join their team you can select
'Join L33tPlayer's Team'

If you would like to play in a pickup game (two teams, large size, clan arena style play)
then join either pickup team red or blue. The number before the pickup team name is the
arena it is in. There may be more than one pickup arena on a level, so make sure you
are joining the correct one.

If you create your own team or join a team that is not already in an arena, you will
then get a menu of arenas on the level. Using the menu, select which arena you want to play
in. Hit ENTER (invuse) to get in line in that arena, or ' (invdrop) to enter the arena
without getting in line. You can observe the matches and get into line at any time
with the observer menu (hit TAB to bring it up).

You can also use ' (invdrop) to observer Pickup Games. Just create a new team and hit
the invdrop key on the Pickup Arena.

Some arenas are set for more than 1 player per team. If you have less than the
maximum number of players, you will be told so, but you can continue into the arena
and people may join your team later.

You cannot enter arenas designed for pickup teams. You must join a pickup team
to get into them.

Gameplay in a Normal/Team Arena
-------------------------------

Once in the arena waiting area, you will wait in line for your chance
against the champion(s). The winning team stays on the battleground until it
is defeated. 

When you enter the arena, a 5 second countdown will begin. Note that there is a
10 second countdown if a vote is pending, to give you time to vote.

You will automatically be given whatever health/armor/weapons/ammo are configured
for that arena. The members of the other team are given the same.

Now you fight.

When all members of one team are dead, the other team is declared the victor.  
If all members of both teams die, a tie is declared and the teams re-enter the arena.

You can optionally vote to turn on rounds in the arena. With rounds on matches
are played in a best X/Y  fashion (2/3, 5/9, etc) with the winning team staying and
the losing team going to the back of the line.

Note that you can always tell your TEAM color by looking at the face on your statusbar.
If you don't see a face there, you aren't in a team arena.

Gameplay in a Pickup Arena
--------------------------

After joining a pickup team you will be placed in the arena as an observer. A match
will probably already have started, and you can watch until the current round is over.
Once the round is over you will be placed in the arena.

Kill everyone on the other team.

When you die you will be placed in observer mode and allowed to watch the rest of the
round. Feel free to cheer for your teammates, but please do not give out health numbers!

Last team standing wins the round. Matches are usually played in matches of (up to) 5,9,
or 11 rounds with a 15 second break in-between matches. Use the break to vote for changes
or switch teams if they become uneven (to switch teams, leave the team you are on and join
the other).

Observer Options
----------------

You may hit TAB to bring up the observer menu. From there you can leave the arena,
get in/out of line, or propose / vote on settings changes. 

"Leave Arena": This will remove your entire team from the current arena and place you
back at the arena selection menu. It is not an option for pickup teams.

"Leave Team": You will be removed from your team and placed at the team selection menu.
If you are the only person on your team, it will be cleared.

"Change Arena Settings": You can propose changes to settings such as: health, armor,
players per team, and weapon mix. Other settings (such as ammo amounts and self
damage) are only configurable by the server op.

"Vote on Changes": When changes have been proposed you will be given notice and can
come here to view/vote on the changes. Always remember to vote on your own proposal!

      Voting Example
      --------------
      For example, say you want to play 2v2 in an arena that is set for 1v1.
      One player should join the arena and propose the changes (and vote for them
      of course). The changes will go through in about 30 seconds.
      He can then have a teammate join his team from the teams menu. Any other
      2 person (or 1 person) team can now enter the arena.
      Please note that if you leave the arena, and it becomes empty, the settings
      are reset to the server default!

Hitting TAB again will remove the menu.

The FIRE key changes observer modes. 
The JUMP key cycles players forwards in trackcam and eyecam mode.
The DUCK key cycles players backwards in trackcam and eyecam mode.

The viewing modes are:
Normal: For arenas with viewing areas, you are placed in the viewing area to watch the match.

FreeFlying: You may noclip freely throughout the level.

TrackCam: RA2 has an excellent trackcam that YOU control. Moving the view will let you fly
around the target you are viewing.

EyeCam: This unique view lets you see EXACTLY what the player is seeing.


Sending Messages
----------------
The default messagemode1 (T key, "say" at console) will only send messages to your
arena. All spectators and players will hear them. If you are in the main waiting
arena, it will be broadcast to the whole server. Arena messages do not play the "beep"
because it can get annoying when playing. If you don't want to hear arena messages
while playing you can set "msg <number>" at the console, where <number> is 2,3, or 4.

The default messagemode2 ("say_team" at console) will send messages to your teammates,
but only if they are in the same state (playing or observing) as you 
(i.e. spectators can't send team messages to teammates that are playing, but two teammates
 playing can communicate this way)

"say_world <message>" at the console will send a message to the entire server.
World messages are prefixed with a W:
When replying to a world message, make sure you use say_world, or your intended recipient
might not hear you (if they are in another arena).
There is no way to bind say_world to a key, but typing text at the console 
(non-commands) will also send it to the world by default.

Spam protection is in effect on the servers. Do not send messages too
fast or you will be kicked (5 messages in 2 seconds would be too fast).

Grapple
-------
This version of Rocket Arena 2 includes (at many players' request) an optional
offhand grapple hook. This can ONLY be turned on by the server admin. If you find
yourself on a server with grapple enabled, and want to try it, just bind a key
to "+hook" and off you go!

In Game Administration
----------------------
See the server readme (readsrv.txt) in the server files for In-Game admin info.

Version Info
------------
2.50: Third public release. 28 Maps (172 Arenas)
2.20: Second public release. 17 Maps (99 Arenas)
2.11: First full public release. 8 Maps (46 Arenas)
2.10: Private beta. 1 Map
2.09: First public beta. 1 Converted map


Design Goals
------------
In correspondence with many people I have referred to the design goals of RA/RA2
when trying to explain design decisions made along the way (or, usually to 
explain why I won't add XYZ snazzy new feature to RA2). So here is a quick
synopsis of the RA / RA2 design goals:
1. To make people into better Quake/Quake 2 players. After playing RA/RA2 for
a period of time, people should go back to Q/Q2 DM/CTF/etc. and find that their skills
have greatly increased. RA/RA2 is intense training.
2. To facilitate a style of deathmatch that is as fair and equal to all participants
as possible. It is no longer an items game, but a test of reflexes and strategy.
3. To keep the emphasis on the game, both for players and observers. Watching other
players is a key to improving one's own skills.
4. To keep the interface / gameplay as simple as possible, while still meeting the
rest of the goals.
5. To preserve the integrity of the game by trying to duplicate Quake/Quake 2 gameplay
as closely as possible. This means keeping the weapon balance, player speed, and other
factors the same. This is important so that when a player goes back to Q/Q2 DM/CTF/etc.
they will not feel that it is an entirely different game, and that their RA/RA2 skills 
are useless. (Quick Note: we have deviated slightly from this principle by adding
VWEP and fast weapon switching to RA2. We justified this by realizing that these two
things will soon become standard features on many other mods as well, and perhaps eventually
in the main Q2 code. They also contribute quite a bit to #6)
6. To have a LOT OF FUN! If you aren't having fun, you must not be playing RA/RA2.


Map Credits
-----------
The Rocket Arena 2 map team did an amazing job on these levels. Feel free to
e-mail them with your questions/comments.

ra2map1      Funkadooda's Alpine Adventure  (7 Arenas)
 Arenas 1 - 5,6: Steve Fukuda <stevefu@unixg.ubc.ca>
 Arena 6: Andrew 'BowZer' Bowser <bowzer@rogers.wave.ca>
 Arena 7: Christian Antkow <xian@idsoftware.com>
 Snow Sky by Jeff Garstecki - www.frag.com/deconstruct
	Arena 1 - Stadium Cargo Hold
	Arena 2 - Alcatraz
	Arena 3 - The Blue Max
	Arena 4 - Funkadooda's Revenge 2
	Arena 5 - Railgun Stadium
	Arena 6 - Drop Zone 
	Arena 7 - The Warehouse

ra2map2      Tesh's Revenge (5 Arenas)
 Arenas 1 - 4: Ralph 'tesh' Gustavsen <clg@coastlinegraphics.com>
 Arena 5: Tim Willits <twillits@idsoftware.com>
	Arena 1 - spongebath
	Arena 2 - rocket jump this!
	Arena 3 - edge of insanity
	Arena 4 - the wicked empty base
	Arena 5 - the outer base

ra2map3      Soahc Complex (3 Arenas)
 Ben Bjoralt (Scalt) <dbjoralt@computerpro.com>
	Arena 1 - DeathBox
	Arena 2 - The Corridors
	Arena 3 - Q2 Soahc

ra2map4      Arenaholics Anonymous (10 Arenas)
 Arenas 1 - 5: Mark Major <shmitz@drchronicles.com>
 Arenas 6 - 10: Tim van Hal <Tim@inside3d.com>
			  Marco van Schriek <Marco@inside3d.com>
			  Roel Tiemessen <Roel@inside3d.com>
			  AKA The MarTim Team
	Arena 1  - Stone Cold
	Arena 2  - Monkies in the Middle
	Arena 3  - The Cage
	Arena 4  - Uneven
	Arena 5  - House of Glass
	Arena 6  - Heart and Soul
	Arena 7  - The Lobbing Lobby
	Arena 8  - Rail Runners
	Arena 9  - Machine Room
	Arena 10 - The Bridge

ra2map5      An Assortment of Flavors (4 Arenas)
 Mackey McCandlish (Avatar) <avatar@widomaker.com>
	Arena 1  - Tek Towers
	Arena 2  - McCandlish Base
	Arena 3  - Sun Baked
	Arena 4  - Only if it Rotates

ra2map6      Fragapalooza (8 Arenas)
 Mark Major <shmitz@drchronicles.com>
 Snow2 Sky by Jeff Garstecki - www.frag.com/deconstruct
	Arena 1 - Courting Death
	Arena 2 - Pillars
	Arena 3 - A Room with a View
	Arena 4 - The Long Jump
	Arena 5 - That Not So Fresh Feeling
	Arena 6 - Gibs on Ice
	Arena 7 - Here and There
	Arena 8 - An Auxiliary Death

ra2map7      Palace of Brak (6 Arenas)
 Ralph 'tesh' Gustavsen <clg@coastlinegraphics.com>
	Arena 1 - Planet Brak
	Arena 2 - Bucket-O-Gibs
	Arena 3 - Spin Cycle
	Arena 4 - Frontdoor-Backside
	Arena 5 - Zoraks Revenge
	Arena 6 - A Good Place to Die

ra2map8      Injury Terminal (3 Areanas)
 Greg Barr <greg@pesky.demon.co.uk>
	Arena 1 - Comm Tower
	Arena 2 - Inferno Compound
	Arena 3 - Ventilation Central

ra2map9      Gizbang (8 Arenas)
 Mike Burbidge (g1zm0) <mikeburb@home.com>
 Thai Pham (SwanSong) <swansong@ienet.com>
 Jack Gaumer (ding0) <ding0@home.com>
 Mark Stottlemyre (ScuNioN) <scunion@home.com.
	Arena 1 - Medieval (g1zm0)
	Arena 2 - Dakyneq2 (g1zm0)
	Arena 3 - Clownfish (g1zm0)
	Arena 4 - Teien (g1zm0)
	Arena 5 - Raligun 101 (SwanSong)
	Arena 6 - Fire Escape (ding0)
	Arena 7 - Madlands (Hyena)
	Arena 8 - Molehills (ScuNioN) 

ra2map10     Rocket O'rena 2 (8 Arenas)
 smeghead <ian@planetquake.com>
 bigOnes <big0nes@planetquake.com>
 MeatHead <meathead@planetquake.com>
	Arena 1 - vigO's Courtyard (big0nes)
	Arena 2 - The Experiment (smegHEAD)
	Arena 3 - Big Ass Ham	(smegHEAD)
	Arena 4 - Heavy Metal	(MeatHead)
	Arena 5 - LavaLands	(big0nes)
	Arena 6 - Uneven Flow	(smegHEAD)
	Arena 7 - The Dive	(big0nes)
	Arena 8 - Oxide (smegHEAD)

ra2map11     Cybernetic Genocyde (7 Arenas)
 Gusty <oldasscheese@hotmail.com>
 Artist <smitac13@oneonta.edu>
 Rico <cyg_rico@hotmail.com>
 G1zm0 <mikeburb@home.com>
	Arena 1 - Loading Zone (Gusty)
	Arena 2 - Stone Manor (Artist)
	Arena 3 - Organized Mass Confusion (Artist)
	Arena 4 - Vertigo (Gusty)
	Arena 5 - Chalice (Rico/Artist)
	Arena 6 - Japang (g1zm0)
	Arena 7 - Storehouse (Rico)

ra2map12      Hal9000's Pimprena (5 Arenas)
 Arenas 1 - 5: John -Hal 9000- Schuch <hal9000@mindspring.com>
 Arena 2: Andrew -LaRd- McIntyre <amcintyre@mcmail.com>
	Arena 1 - The Suck Tube
	Arena 2 - The Law
	Arena 3 - FragHack
	Arena 4 - The Other Warehouse
	Arena 5 - Uberena

ra2map13      The Proving Grounds (4 Arenas)
 David M. Mertz (Alpha_Male) <dmertz@vt.edu>
	Arena 1 - Against the Flow
	Arena 2 - Rib Cage
	Arena 3 - Arena M I
	Arena 4 - Over Pass

ra2map14     Rocket O'rena 1 (5 Arenas)
 smeghead <ian@planetquake.com>
 bigOnes <big0nes@planetquake.com>
 MeatHead <meathead@planetquake.com>
	Arena 1 - Intestinal Fortitude (smegHEAD)
	Arena 2 - Forgotten Base (big0nes)
	Arena 3 - Rapid Violence (smegHEAD)
	Arena 4 - Midnight Madness (MeatHead)
	Arena 5 -  Back Alley Rumble! (smegHEAD)

ra2map15     KarNiX's Rage (6 Arenas)
 Arenas 1-4,6: KarNiX <KarNiX@powersurfr.com>
 Arena 5: Deathstalker <maclean@wcoil.com>
	Arena 1 - The Platform
	Arena 2 - The Factory
	Arena 3 - The Dock
	Arena 4 - Cooling Factory
	Arena 5 - Twilight's Temple
	Arena 6 - PointBlank's Base

ra2map16     MAHQ Contest Map (5 Arenas)
 Deathstalker <maclean@wcoil.com>
 NoFadz <starless@nofadz.com>
 Chesire <calypso@iinet.net.au>
 Red2 <red2@nw.com.au>
 MeatHead <meathead@planetquake.com>
	Arena 1 - Valium (Chesire)
	Arena 2 - The Deserted Cistern (DeathStalker)
	Arena 3 - Go With the Flow (Red2)
	Arena 4 - The Abandoned Fort (NoFadz)
	Arena 5 - The Temple (pickup) (MeatHead)

ra2map17     The Asylum (5 Arenas)
 MAD|Forrest <rcoulomb@total.net>
	Arena 1 - Gymnasium
	Arena 2 - Melissa's Fancy
	Arena 3 - Bloody Waste
	Arena 4 - Mad Mines
	Arena 5 - cbase

ra2map18     Malicious Carnage (6 Arenas)
 DeathStalker <maclean@wcoil.com>
	Arena 1	- Beggars Canyon
	Arena 2	- Toshi Station
	Arena 3	- Gladatorial
	Arena 4	- Tidal
	Arena 5	- Twilight's Temple v2
	Arena 6	- Inside Outside (Pickup)

ra2map19     Futterville's Joint by MAHQ (6 Arenas)
 big0nes <big0nes@planetquake.com>
 smegHead <ian@planetquake.com>
 Meathead <meathead@planetquake.com>
	Arena 1 - Gothic Mayhem (MeatHead)
	Arena 2 - Diet Smack (smegHEAD)
	Arena 3 - The Observatory (big0nes)
	Arena 4 - The Fuel Depot (big0nes)
	Arena 5 - SquareDeath (smegHEAD)
	Arena 6 - Pumping Station (MeatHead)

ra2map20     MAHQ Contest Winners 2A (5 Arenas)
 big0nes <big0nes@planetquake.com>
 Karnix <KarNiX@powersurfr.com>
 DeathStalker <maclean@wcoil.com>
 Billy <dverwer@globalnet.co.uk>
 Geburah <geburah@phase2.net>
	Arena 1 - Cargo Bay (Karnix)
	Arena 2	- Kinslayer (Deathstalker)
	Arena 3	- Dry Dock (Billy)
	Arena 4	- Sling Shot (Geburah)
	Arena 5	- The Other Side (Tim Willits/big0nes)

ra2map21     MAHQ Contest Winners 2B (5 Arenas)
 Meathead <meathead@planetquake.com>
 Deadstar <deadstar@terrafusion.com>
 MiTeS <jhitt@texas.net>
 Stony <ms_stony@gmx.net>
 Perse <perse@schoolmail.com>
 Thanatopsis <andrew@palmernet.demon.co.uk>
	Arena 1 - Recoil (Deadstar)
	Arena 2	- Brick Oven (MiTeS)
	Arena 3	- Cross (Stony)
	Arena 4	- Middle of Rationality (Perse)
	Arena 5	- The Boilerhouse (Thanatopsis)

ra2map22     Alpha's Eclectic Collection (8 Arenas)
 Alpha_Male <dmertz@vt.edu>
	Arena 1	- The Coolant Bed 
	Arena 2	- No Contact I
	Arena 3	- No Contact II
	Arena 4	- No Contact III
	Arena 5	- No Contact IV
	Arena 6	- The Grotto
	Arena 7	- TransLev
	Arena 8	- The Caldera

ra2map23     Virtuosity (4 Arenas)
  Deadstar <deadstar@terrafusion.com>
	Arena 1	- Titanium Tomb
	Arena 2	- Full Frontal
	Arena 3	- Dead's Tower
	Arena 4	- Shifted Paradigm 

ra2map24     Big0nes DM Sampler (4 Arenas)
 big0nes <big0nes@planetquake.com>
	Arena 1 - Slice of Heaven
	Arena 2 - A Tokay Tower
	Arena 3 - Watery Grave
	Arena 4 - Desperation

ra2map25     Adrenaline Rush (11 Arenas)
 keno <kenodman@hotmail.com>
	Arena 1 - Rush
	Arena 2 - Lava Dome
	Arena 3 - Frag or Die
	Arena 4 - Holy Water	
	Arena 5 - Shadow of the Damned
	Arena 6 - Pandamonium
	Arena 7 - The Fort
	Arena 8 - The Other Fort
	Arena 9 - Gotcha!
	Arena 10 - Underground
	Arena 11 - The Castle

ra2map26     Fack's Arena (7 Arenas)
 fack <fack@cgocable.net>
	Arena 1 - Circular Chaos
	Arena 2 - The Halfpipe
	Arena 3 - King of the Hill
	Arena 4 - Military Massacre
	Arena 5 - Cavernous Carnage
	Arena 6 - Heads up
	Arena 7 - The Pit

ra2map27     RA2 All Stars Map 1 (8 Arenas)
 Steve Fukuda <stevefu@unixg.ubc.ca>
 Ben Bjoralt (Scalt) <dbjoralt@computerpro.com>
 NoFadz <starless@nofadz.com>
 Mike Burbidge (g1zm0) <mikeburb@home.com>
 MAD|Forrest <rcoulomb@total.net>
 Q2DM1 - "The Edge" by Tim Willits of Id Software
	Arena 1 - Funkadooda's Revenge (funkadooda)
	Arena 2 - Railgun Stadium (funkadooda)
	Arena 3 - Deathbox (scalt)
	Arena 4 - Drop Zone (funakadooda)
	Arena 5 - Abandoned Fort (nofadz)
	Arena 6 - Clownfish (g1zm0)
	Arena 7 - Melissa's Fancy (forrest)
	Arena 8 - The Edge - by Tim Willits of Id Software

ra2map28     RA2 All Stars Map 2 (8 Arenas)
 Ralph 'tesh' Gustavsen <clg@coastlinegraphics.com>
 Jack Gaumer (ding0) <ding0@home.com>
 Mike "big0nes" MacDonald <big0nes@planetquake.com>
 Mackey McCandlish (Avatar) <avatar@widomaker.com>
 Greg Barr <greg@pesky.demon.co.uk>
  Rico <cyg_rico@hotmail.com>
	Arena 1 - Edge of Insanity (tesh)
	Arena 2 - Storehouse (Rico)
	Arena 3 - Fire Escape (ding0)
	Arena 4 - vig0's Courtyard (big0nes)
	Arena 5 - Comm Tower (Greg Barr)
	Arena 6 - Sun Baked (Avatar)
	Arena 7 - SpongeBath (tesh)
	Arena 8 - HIPDM1 - by LevelLord, Q2 Version by BlueSeed

Other Credits
-------------
Big thanks to the beta testers and mailing list members for all their
bug reports and ideas. Some stuff that we couldn't put in this version will
certainly find its way into later ones.
To Tesh, for the awesome RA2 web site design.
To Yujin for the console background.
To Artist (smitac13@snyoneva.cc.oneonta.edu) for donating the new RA2 skins
To Clan McP (www.clanmcp.com), for testing all the new maps.
To Dennis "Meathead" Urie and Will "Jumping Bean" Seay for their help in testing.
Finally, I would like to thank Basty, dweomer, Fargo, and the rest of the PlanetQuake
guys for all their support and resources.

Copyright and Distribution Permissions
--------------------------------------

This patch is freely distributable provided that this readme is distributed
as well and is unchanged.

All code is Copyright David Wright 1998-1999.
Commercial code licensing is available by contacting wrightd@gamespy.com

DISCLAIMER:  This patch is 100% safe, tested, and FDA approved,
so you should have no trouble with it. But if you do.. its not our fault.
DLL's always carry an inherent risk for servers, but as a client, you run no
code outside of Quake2 itself. So don't worry, be happy!

Availability
------------

This modification is available from the following places:

http://www.planetquake.com/arena