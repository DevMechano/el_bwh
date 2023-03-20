# el_bwh
FiveM Ban/Warning/Help-Assist System for FPX

# info
- Ban system reworked for [fpx]
- This is not my script, it's just modified

## Installation
1. Rename it to `el_bwh` and put it in your resources folder
2. Import sql.sql into your database
3. Edit the config to your liking
4. Add `ensure el_bwh` to your server.cfg ***Make sure to add this after mysql-async and es_extended***
5. Start it and you're good to go

## ***Documentation ***
There's a few commands this adds:
- /bwh             <- root admin command, this will display all sub-commands
- /bwh ban         <- opens the ban menu
- /bwh warn        <- opens the warn menu
- /bwh banlist     <- opens the ban list
- /bwh warnlist    <- opens the warning list
- /bwh assists     <- shows pending/active assists in the chat
- /bwh refresh     <- pulls all bans from the database and refreshes the ban cache
- /accassist       <- admin command, admins can accept help requests from players
- /finassist       <- admin command, this closes the current help request and teleports you back to your original position
- /decassist       <- admin command, this just hides the current assist popup on the screen
- /assist          <- player command, players can request help with this
- /cassist         <- player command, this cancels the players ongoing assist request  

To unban someone, go to the ban list and scroll far right to the "Actions" section, you'll find a green unban button there
