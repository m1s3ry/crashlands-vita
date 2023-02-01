# crashlands-vita
A patch to make Crashlands playable on the PS Vita

###

## Disclaimer
This patch does not contain any game files from Crashlands. **You need the game files from your legally owned copy**.
If you don't have a copy of the game, you can buy it [HERE](https://store.steampowered.com/app/391730/Crashlands/)
It **WILL NOT WORK* with an illegal copy of the game due to hash check.

## Instructions (Read them carefully)

**IMPORTANT (1):** The patch does not work with current version of the game in Steam. Here's how to get game files of supported version on Steam.
1. Open the [Steam console](https://steamcommunity.com/sharedfiles/filedetails/?id=873543244)
2. Download specific version of the game by typing this command: `download_depot 391730 391731 750708251145921383`. It may look like it doesn't do anything, but wait a few minutes
3. When the downloading is done, you will see this message: `Depot download complete : [PATH_TO_THE_DOWNLOADED_GAME_FILES]`
4. Go to the folder and run the path there.

**Normal installation:**
1. Download the VPK and install it on your hacked PS Vita
2. In your PC, open the folder when you have installed Crashlands (Steam using previous IMPORTANT (1) instruction)
3. Download the patch for your version and extract it in that folder. After that, run `apply_patch.bat`. This will create a folder called `Patched_Files`
4. If everything went correctly, your Patched_Files folders will have a file called `eboot.bin` and a folder called `games` with a lot of `audiogroup.dat` files and a `game.win` file.
5. Copy `eboot.bin` and the `games` folder and move them to the vita, `ux0:app/CRASHLAND.` Overwrite when prompted. 
6. Copy all the `.ogg` files from your PC Crashlands folder into `ux0:app/CRASHLAND/games` 
7. Optional: Overclock your CPU to 444mhz with PSV Shell to mitigate some microstuttering.

**IMPORTANT (2):** This patch is not confirmed to work with any other version that it's not the current latest build of Steam. It _should_ support other versions but it's very likely it won't properly.

## Known Problems
* Loading times are pretty long, so don't be afraid, your Vita didn't crash. About 2 minutes.
* Autosave is not super reliable. Use manual save too (just press Select for quicksave)

## Credits
Credits for the original game go to Butterscotch Shenanigans team.

@theyankeewithnovim for helping me with technical stuff

Additional credit for the port goes to @Grossleymoo for UTMT and helping/teaching me to port Vita games.

Kubitini for making the updated instructions for how to get the correct version

## Donations
If you want to support my work, you can [buy me a coffee here!](https://www.buymeacoffee.com/m1s3ry)

Also you can [follow me on twitter](https://www.twitter.com/m1s3ry_)
