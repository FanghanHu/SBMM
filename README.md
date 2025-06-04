# SBMM
A Skill based matchmaking tool.

## Player preferences
Players can whitelist and blacklist maps and rules.
Player can set a skill score offset range, only other player within this range will be matched with this player.

## map and rule selection
the maps and gamerules can be configured with a weighting value, when players matched with multiple preffered maps/rules, the actual map/rule a game use is selected randomly based on this weight setting.

## Matchmaking modes
Two modes are to be provided:
*   Quick match
    *   player are automatcally placed into the first match found.
*   Select mode
    *   Player are given options of multiple matches where player can "ready up" for multiple of them, once one of the games the player readied for has enough player, the player is placed in that game.

