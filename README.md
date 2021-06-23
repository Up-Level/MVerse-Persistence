# MVerse Persistence
A Creeper World 4 CPACK which persists client MVerse units, meaning they are stored in a save file.

By default, CW4 duplicates the host's units when a saved MVerse game is loaded. This pack spawns each players units (including custom units) separately when an MVerse session is started, meaning multiplayer games can be stopped then later resumed.

However, there are a few limitations:
- The Rift Lab position of each player is not saved.
- Air Units' target location is not saved.
- Players must join the session in the same order as they did previously.
- The host MUST press the defined save hotkey before they save the game the normal way. However, there is an autosave every minute meaning if you forget not all progress is lost.

Custom units *should* work, though of course I can't test every custom unit so it might not work very well at times.
