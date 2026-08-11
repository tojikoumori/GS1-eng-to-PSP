# Gyakuten Saiban 1 / Phoenix Wright: Ace Attorney GBA to PSP

<script type="text/javascript" src="https://cdnjs.buymeacoffee.com/1.0.0/button.prod.min.js" data-name="bmc-button" data-slug="tojikoumori" data-color="#102457" data-emoji="☕"  data-font="Inter" data-text="Buy me a coffee" data-outline-color="#ffffff" data-font-color="#ffffff" data-coffee-color="#FFDD00" ></script>

This is a project about Gyakuten Saiban / Ace Attorney 1 for GBA that releases: last missing case 4 english patch, a .sav with all cases unlocked, a builder for the game to have its own XMB entry for PSP, and a patch to make the characters voices sfx hearable (blips).

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

1. Download [FrogGBA](https://github.com/tzubertowski/FrogGBA) , and everything in the XMB Builder release
2. Place the contents of the XMB Builder release in a folder, with FrogGBA and your ROM
3. Make sure that your FrogGBA folder has a copy of `gba_bios.bin` placed in its root
4. Run the .bat and optionally configure the emulator's settings inside it
5. It will build a folder, ready to drop into this directory inside your PSP SD card! -> PSP > GAME

## [Optional] Using the save file

simply place it into the "save" folder inside your freshly built folder / frogGBA folder. 

