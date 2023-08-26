**afk:**
/afk and /back chat commands, pretty self explantory

**betting:**
a pvp tool
- /acceptduel - Accepts the current duel request.
- /acceptffa - Accept the current ffa request.
- /cancel - Cancel the current duel/ffa request.
- /duel <amount> - Create a duel request to the targeted player. Winner gets the pot.
- /ffa <amount> - Create an ffa and send an invite to everyone in the system. Winner gets the pot.
  
**bountyhunt:**
The "Bounty Hunt" plugin allows players to put bounties on each other that can be collected by destroying that player.
- /bountyhunt <player> <amount> [timelimit] - Places a bounty on the specified player. When another player kills them, they gain <credits>.
- /bountyhuntid <id> <amount> [timelimit] - Same as above but with an id instead of a player name. Use /ids to see IDs

**deathpenalty:**
currently disabled
This plugin charges players credits for dying based on their ship worth. If the killer was a player it also rewards them.
  
**kill_tracker:**
This plugin is used to count pvp kills and save them in the player file.
Also keeps track of damage taken between players, prints greatest damage contributor.
- /kills {client} - Shows the pvp kills for a player if a client id is specified, or if not, the player who typed it.

**tax:**
The Tax plugin allows players to issue 'formally' make credit demands and declare hostilities.
- /tax <credits>
- /tax