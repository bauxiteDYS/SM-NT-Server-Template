# Server template for Neotokyo with Sourcemod plugins and configs  

### Installation instructions for Windows:

1. Download the Neotokyo server files - APPID `313600`.
2. Download the latest stable Sourcemod (>= 1.11) and the latest dev-branch Metamod (>= 1.12) and copy them to your server files.
3. Copy the included `NeotokyoSource` folder over the top of the default, replace everything.
4. Un-disable the base plugins - `nominations.smx` and `rockthevote.smx`.
5. Modify server and others cfgs to your liking, passwords, stv, admins.cfg, maplists, clantags.cfg, veto_maplist, motd and advertisements etc.
6. Start the server with the command file `start_server.cmd` - it will automatically restart after a crash.
7. Enjoy.

#### Notes:  

- The `bin\dedicated.dll` included is not required but it may help to reduce CPU usage if you are encountering issues.
- Code for plugins and some additional plugins is included in the scripting folder, check `addons\disabled` for optional plugins etc.
- The optional `srcds_console.exe` is from the Alien Swarm Reactive Drop files, can be used to get a somewhat working console on Linux, works on Windows aswell.
- MOTD with html elements doesn't display for players using Linux.  

### Installation instructions for Linux:   

1. Read above.
2. Use WINE to run the server files on Linux as explained in this guide:
`https://steamcommunity.com/sharedfiles/filedetails/?id=282277252`
3. Seems to work just fine, might need the "dedicated.dll" to reduce CPU usage.

**NOTE:** If you use `srcds_console.exe` you do not require xvfb. Start like: 
`wine srcds_console.exe -console -tickrate 66 ...` etc  

## Credits:   

I put together these files and guide, however I could not have done it without help from the NT community, the players and the individuals who coded the plugins, wrote other useful guides: Rain, Agiel, SoftAsHell, Glubsy, Phorce, Kudegra, Dennogin, Hosomi, Lilihierax, Oni, Dommler, Lizard, Kino, Kang aka You're pissed Off, Alpha - Just to name a few.
