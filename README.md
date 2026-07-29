# Gyakuten Saiban 1 / Phoenix Wright: Ace Attorney GBA - Case 4 ENG patch, full save, PSP XMB entry 
This is a project about Gyakuten Saiban / Ace Attorney 1 for GBA that releases: last missing case 4 english patch, a .sav with all cases unlocked, and a guide to make the game have its own XMB entry for PSP! 

You can now play this game fully in english, applying this and another patch made by h3rmit and spazzery (all credits to them for that!), which translates the first 3 cases. [Download their patch here](https://www.gamebrew.org/wiki/Phoenix_Wright_-_Ace_Attorney_GBA)

---------------------------
<sup>i make projects for fun and share them to use freely, though i spend so much time on them, 

<sup>so if this was of use to you and you want to support me i appreciate donations :)<sup>

<sup>☕ https://buymeacoffee.com/tojikoumori<sup>

---------------------------
# Applying the patch

You should apply this patch on top of the case 1-3 one.

Use an IPS patcher to apply the English patch to your Japanese ROM:

**Using [Floating IPS](https://www.romhacking.net/utilities/1040/) (Windows/Linux):**
1. Open FLIPS
2. Click **Apply patch**
3. Select both of the `.ips` files
4. Select your Gyakuten Saiban ROM
5. Save as a new file

# PSP XMB Entry guide
<img width="1023" height="572" alt="Screenshot_2026-07-28-19-46-05-036_com miui gallery-edit" src="https://github.com/user-attachments/assets/dc3b1a48-a95e-47b2-b17e-19f188aa66e5" />

_The end result will appear just like a normal game on your XMB. It will be running through the FrogGBA emulator, although you won’t see the emulator menu at all — the game will launch straight away._ 


## Creating the EBOOT 

1. Download [FrogGBA](https://github.com/tzubertowski/FrogGBA) , and everything in the Utilities release
2. Place the contents of the Utilities release in a folder
3. Have your FrogGBA folder ready, with a copy of `gba_bios.bin` placed in its root
4. Double click `froggba_xmb.py` and follow what it says - it will ask you to point it to your FrogGBA/ROM/ICON0/PIC1 paths, and about some settings preferences
5. It will build a folder, ready to drop into this directory inside your PSP SD card! -> PSP > GAME

## [Optional] Using the save file

This is also included in the Utilities release - simply place it into the "save" folder inside your freshly built folder / frogGBA folder. 

