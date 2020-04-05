# Quake II Server Console Commands

cvarlist
Type: Operation
Description: Display a list of all variables, their flags, and their values.

Note: Each varaiable has a value and a state flag. If a variable has the value of "", then that variable is empty.

List:
* - Saved setting, will save changes to this variable between games by writing it in the config.cfg file.
U - User variable, will show up in the output from the userinfo command or dumpuser command..
S - Server variable, will show up in the output from the serverinfo command.
L - Delayed function, will take action after a map change.
- - Write protected, only changable upon launching of the game with a command line parameter.


exec
Type: Function
Syntax: exec (filename)

Description: Execute a console script file.

Note: This is a very helpful command because it allows for the execution of multiple commands which are stored in text files and are used to setup the client or a server. The default extension for a console script is .cfg, but an extension of .rc is also in common use especially for player configuration scripts. The .rc extension was derived from Unix shell scripts which also share the same extension.

Example: exec foo.rc


rcon
Type: Function
Syntax:
rcon (password) (command)
rcon (command)
Description: Remotely control a server.

Note: This command is used to control a server from a client. This is very useful if the server is running at a remote location, and the server administrator does not have physical access to the server. There are two different syntax versions to this command. If the variable rcon_password is set the second syntax may be used since the password field will be filled automatically by the client. Also, be aware that it is possible to send commands to a server to which the client is not connected. This is accomplished with the setting of the rcon_address variable to the server's IP address. Using the command, a server administrator is able to control a server as if at the server's console.

Example:
rcon foo "map base1"
rcon "map base1"

dmflags
Type: Bitmap
Default: 16
Description: The options which determine deathmatch game settings.

Values:
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



| Command                | Default | Description | Notes |
| :--------------------- | :------ | :---------- | :---- |
| allow_download         | 0       | Toggle the automatic downloading of game files. | Can be used by both, the client and the server individually to prevent the automatic downloading of game files. |
| allow_download_maps    | 1       | Toggle the automatic downloading of map files to the client from the server. | can be used by both, the client and the server individually to prevent the automatic downloading of game files. Maps which are contained in .pak files will not be available for download because of copyright issues associated with the distribution of commercial addons. |
| allow_download_models  | 1       | Toggle the automatic downloading of model files. | can be used by both, the client and the server individually to prevent the automatic downloading of game files. |
| allow_download_players | 1       | Toggle the automatic downloading of player skin files. | can be used by both, the client and the server individually to prevent the automatic downloading of game files. |
| allow_download_sounds  | 1       | Toggle the automatic downloading of sound files. | This command can be used by both, the client and the server individually to prevent the automatic downloading of game files. |
| cl_maxfps              | 90      | The maximum number of packets-per-second the server should send to the client to cap the frames-per-second rate. |
| filterban              | 1       | Toggle the usage of the banlist. | 0 - Allow only the addresses in the banlist to join the server. 1 - Ban the addresses in the banlist from joining the server. |
| gamemap                |         | Start the server with a new map. Example: `gamemap base1` | The extension .bsp is appended to the (filename) when it does not include an extension. |
| hostname               |         | Sets the name of the server | |
| kick                   |         | Remove a client from the server. Example: `kick (userid)` / `kick (username)` | You can remove clients from the server by their (userid) or by their (username). |
| killserver             |         | Shutdown the server. | This command will terminate the server, but it will not exit from the server's console. This is useful when changing mods for the server remotely. |
| logging                | 0       | Toggle the logging of console messages. | 0 - Disable logging. 1 - Enable buffered logging where the log file is only updated when the text buffer fills up. The log file will be deleted and overridden when a new server starts up. 2 - Enable continuous logging where the log file is updated with every new line of text. The log file will be deleted and overridden when a new server starts up. 3 - Enable continous logging where the log file is updated with ever new line of text. The log file will be appended to and logging will continute to the same log file when a new server starts up. |
| maxclients             | 1       | The maximum number of clients for the server. | |
| maxspectators          | 4       | The maximum number of spectators for the server. | |
| password               | ""      | The server password. |  If this variable is set to none then no password is required to enter the server. |
| port                   | 27910   | The TCP/IP port number used by the server. | |
| public                 | 0       | Toggle listing server in id's master server list. | |
| rate                   | 2500    | The maximum number of bytes that the server should send to the client. | |
| spectator_password     | ""      | Set the password necessary to join the server as a spectator. | If this variable is set to the string none then anybody can enter the server as a spectator without a password, this is in order to allow the usage of rcon to reset the password. |
| status                 |         | Display server status. | |
| sv_airaccelerate       | 0       | The maximum additional allowable air acceleration velocity. | Normally this variable is set to 0 and players have no control of their velocity when in air. If this variable is increased then players will be able to control their velocities in mid-air allowing them more control of their movement. If you wish to make the air control the same as in Quake and QuakeWorld then you should set this variable to a value of 10. This variable is ignored for single-player and cooperative games. |
| sv_enforcetime         | 0       | Toggle the enforcing of time measurements between the client and the server. | |
| sv_gravity             | 800     | The gravity in the game. | |
| sv_maplist             |         | The list of maps that the server cycles through. | Example: `sv_maplist "base1 biggun q2dm1 boss2 fact1 q2dm2 fact3 hangar1"` |
| sv_maxvelocity         | 2000    | The maximum velocity for any moving object. | |
| sv_noreload            | 0       | Toggle the reloading of all the game data for every map. | |
| sv_reconnect_limit     | 3       | The number of times that a client can reconnect to the server. | |
| timeout                | 125     | The maximum number of seconds before terminating a game connection. | If no packets are sent from the client to the server within that time range the server will disconnect the client from the game. |
