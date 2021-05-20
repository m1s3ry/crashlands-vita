# crashlands-vita
A patch to make Crashlands playable on the PS Vita

###

## Disclaimer
This patch does not contain any game files from Crashlands. **You need the game files from your legally owned copy**.
If you don't have a copy of the game, you can buy it [HERE](https://store.steampowered.com/app/1503530/Minit_Fun_Racer/)
It **WILL NOT WORK* with an illegal copy of the game due to hash check.

## Instructions (Read them carefully)
1. Download the VPK and install it on your hacked PS Vita
2. In your PC, open the folder when you have installed Crashlands (Steam, Epic Games Store or GoG)
3. Download the patch for your version and extract it in that folder. After that, run `apply_patch.bat`. This will create a folder called `Patched_Files`
4. If everything went correctly, your Patched_Files folders will have a file called `eboot.bin` and a folder called `games` with a lot of `audiogroup.dat` files and a `game.win` file.
5. Copy `eboot.bin` and the `games` folder and move them to the vita, `ux0:app/CRASHLAND.` Overwrite when prompted. 
6. Copy all the `.ogg` files from your PC Crashlands folder into `ux0:app/CRASHLAND/games` 
7. Optional: Overclock your CPU to 444mhz with PSV Shell to mitigate some microstuttering.

**IMPORTANT:** This patch is not confirmed to work with any other version that it's not the current latest build of Steam. It _should_ support other versions but it's very likely it won't properly.

## Known Problems
* Loading times are pretty long, so don't be afraid, your Vita didn't crash. About 2 minutes.

## Credits
Credits for the original game go to Butterscotch Shenanigans team.
Additional credit for the port goes to @Grossleymoo for UTMT and helping/teaching me to port Vita games.

## Donations
If you want to support my work, you can [buy me a coffee here!](https://www.buymeacoffee.com/m1s3ry)

Also you can [follow me on twitter](https://www.twitter.com/m1s3ry_)
