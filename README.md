# Galactic-Missile-Defense-Vita
A port/patch to make the game **Galactic Missile Defense** (Steam Version) playable on the PSVita.

###

## Disclaimer
**The provided files in this repository do not contain any game files.**

To be able to use the provided patch and actually play the game in your PSVita, **you need to legally buy the game on the Steam platform**.

You can buy a copy here: [https://store.steampowered.com/app/388550/Galactic_Missile_Defense/](https://store.steampowered.com/app/388550/Galactic_Missile_Defense/)

## Instructions
1. Download the VPK file that is provided in here, along with the ZIP file containing patch information.
2. Extract the ZIP to a temporary folder.
3. Locate your **Galactic Missile Defense** Steam installation folder. You should only have 1 file, named **"GMD_Steam.exe"**
4. Open the **"GMD_Steam.exe"** file with WinRAR, WinZIP, 7z or a similar software. You'll notice a lot of files within it.
5. Extract the **"data.win"** file from within the **"GMD_Steam.exe"** file, along with all the **".OGG"** files present.
6. Copy that **"data.win"** file into the previously created temporary folder. Make sure the file is placed in the same location as all the other files present in the ZIP.
7. Double click the "apply_patch.bat" file, a command-line window will open and will start patching automatically.
8. Once patching is complete you will find your new **"game.win"** file in the main folder.
9. Install the VPK file into your PSVita.
10. **Copy the "game.win" file into the "ux0:app/GAMIDEF00/games" folder.** Make sure to replace the dummy file that's present there.
11. **Copy every extracted .OGG file into the "ux0:app/GAMIDEF00/games" folder as well.**
12. (Optional) You can delete the **"main_bgm.ogg"** music file present in there to save 2MB of free space.
13. Have Fun!

## Hashes
The hash information of your **original, unaltered Steam "data.win"** file should be:

**MD5**: 6830aae194696f853189497b5c670262

**CRC32**: acb1356b

The hash information of your **modified, PSVita ready "game.win"** file should be:

**MD5**: cb93a16363520366704c1fff0c34f8ef

**CRC32**: 29f048c9

If these hashes do not match, then something went wrong.

## Things to keep in mind:
1. This game is **fully touchscreen**. No buttons are used.
2. **The title screen is a little low FPS. This is normal and only happens here. Don't worry, in-game does not suffer from low FPS.**
3. The game saves automatically when you purchase items on the shop, lose or exit gameplay, so you can press the PS button and exit the game in the shop menu safely.
4. Since this is one of those games with in-app purchases, and since those are unavailable in the PSVita, you start the game with 10.000 credits to buy upgrades and stuff.
5. Difficulty has also been adjusted in the game to adjust to the PSVita.

## Credits
Big Special Thanks to the "BlackSheep Games" devs for releasing the source code and SilicaAndPina for the GayMaker tool.
