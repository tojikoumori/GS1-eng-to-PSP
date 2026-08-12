# Gyakuten Saiban 1 / Phoenix Wright: Ace Attorney GBA to PSP

This is a project about Gyakuten Saiban / Ace Attorney 1 for GBA that releases: last missing case 4 english patch, a .sav with all cases unlocked, a builder for the game to have its own XMB entry for PSP, and a patch to make the characters voices sfx hearable (blips) - since you originally could barely hear it.

------------------
You can now play this game fully in english, applying this and another patch made by h3rmit and spazzery (all credits to them for that!), which translates the first 3 cases. [Download their patch here](https://www.gamebrew.org/wiki/Phoenix_Wright_-_Ace_Attorney_GBA)

# Applying the patch/es

You should apply the case 4 patch on top of the case 1-3 one.

Use an IPS patcher to apply the English patch to your Japanese ROM:

**Using [Floating IPS](https://www.romhacking.net/utilities/1040/) (Windows/Linux):**
1. Open FLIPS
2. Click **Apply patch**
3. Select both of the `.ips` files
4. Select your Gyakuten Saiban ROM
5. Save as a new file

# PSP XMB Entry guide
<img width="1023" height="572" alt="Screenshot_2026-07-28-19-46-05-036_com miui gallery-edit" src="https://github.com/user-attachments/assets/dc3b1a48-a95e-47b2-b17e-19f188aa66e5" />

_The end result will appear just like a normal game on your XMB. It will be running through the FrogGBA emulator, although you won’t see the emulator menu at all — the game will launch straight away._ _note: you might see the emulator menu the first time you launch the game_ 

_You need the rebuilder mainly to safely rename the eboot, some settings selected from there currently don't persist._

## Creating the EBOOT 

1. Download [FrogGBA](https://github.com/tzubertowski/FrogGBA) or [ToadGBA](https://github.com/AlfonsoVM/ToadGBA/releases/tag/v1.0.43) (an improved fork of the first one) , and the zip in the XMB Builder release
2. Extract the zip and place FrogGBA/ToadGBA and your ROM in it
3. Make sure that your FrogGBA/ToadGBA folder has a copy of `gba_bios.bin` placed in its root
4. Run the .bat, it will build a folder, ready to drop into this directory inside your PSP SD card! -> PSP > GAME

## [Optional] Using the save file

simply place it into the "save" folder inside your freshly built folder / frogGBA / ToadGBA folder. _note: if using ToadGBA, you should place your save in its root as well._

