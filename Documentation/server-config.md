# Quake II Dedicated Server Guide

source: http://planetquake.gamespy.com/View4679.html

## Basics

The best place to start is by making sure you can start a basic dedicated server and that you can get it to ping the master server so it will be seen on the internet.  We will not worry yet about all the command you want in your server, if it doesn't run or reach the internet, setting the weapons and respawn time won't help. If you have already accomplished this, go on to the next section.

First, pick your favorite mod and make sure you have the server files for it.  FilePlanet will have what you need. Some mods will have a readme for running the server, and some will have a sample config for you to see their specific settings for things like power-ups etc... Please take a good look at it.

To initialize your server you need a batch file.  The easiest way to make this is to create a shortcut on your desktop of Quake2.exe.  Right click that icon, go to Properties.  In the target field you will use the following lines:

``` text
+set dedicated 1 - this sets the server to dedicated (will not run the game, only a server)
+set game nameofmod - the name of your mod goes here, such as ctf, lithium, chaos...(or none if you want just regular old Quake 2)
+map q2dm1 - you need the first map in your rotation in the batch file otherwise in your server.cfg
+exec server.cfg - executes your server config (see below)
```

To add these to your target line you need to type:

{space}+set dedicated 1 +set game lithium +map q2dm1 +exec server.cfg

## Server.cfg

This gives the information about your server. Open Notepad and add what you want to it.  See the examples below:

``` text
set hostname "Love2Play's server" - Whatever you want to name your server
set master q2master.planetquake.com - this sends a heartbeat to the master server
set location Western US - tells the master where you are located.
set website "http://www.planetquake.com" s - If you have a website you want others to visit
set maxclients 12 - limit number of people who can join
set public 1 - sets your server as public, otherwise will not go out on the internet
set timelimit 15 - timelimit of each map round
set fraglimit 40 - limit number of frags per round
```

Make changes accordingly, we don't need a thousand Quake 2 servers out there called Love2Play's server.  Although flattering, get your own name! Then choose Save As and save it as server.cfg and place it in your Quake2\baseq2 folder.

Then you have other things to choose from.  A few more specifications.... for example deathmatch flags. These are number values that represent a group of settings.  Like so:

1 - No Health.
2 - No Powerups.
4 - Weapons Stay.
8 - No Falling Damage.
16 - Instant Powerups.
32 - Same Map.
64 - Teams by Skin.
128 - Teams by Model.
256 - No Friendly Fire.
512 - Spawn Farthest.
1024 - Force Respawn.
2048 - No Armor.
4096 - Allow Exit.
8192 - Infinite Ammo.
16384 - Quad Drop.
32768 - Fixed FOV.
131072 - CTF Forced Join.
262144 - Armor Protect.
524288 - CTF No Tech Powerups.

The way you set your deathmatch flags is by adding the value of your selected commands.  For example;  Weapons Stay, Same Map, Spawn Farthest, and No Armor would be 4 + 32 + 512 + 2048 = 2596.  In your server.cfg add the line: set dmflags 2596
