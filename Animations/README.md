Here are the animations I made for Flipper Zero. Those are folder-sorted by theme with preview videos* :

- [Rogue Master Themed](https://github.com/Kuronons/FZ_graphics/tree/main/Animations/Custom_Firmwares) - Dedicated to Rogue Master



**TO INSTALL ON YOUR FLIPPER ZERO :**

1. Download animation zip file on your PC.<BR>
   (.zip file contains a folder holding the animation frames .bm files and there corresponding meta.txt)

2. Unzip and drag&drop / copy&paste the folder<BR>
-> If your are under official, Unleashed or RogueMaster firmware : into your flipper's ***SD/dolphin/*** folder.<BR>
-> If you are under Momentum or Xtreme firmware : into your flipper's asset pack folder (***SD/asset_packs/yourcustompacknamehere/Anims/***).
    
3. Manifest<BR>
-> Edit your manifest ***SD/dolphin/manifest.txt*** (OFW, UL or RM)<BR>
-> or create one ***SD/asset_packs/yourcustompacknamehere/Anims/manifest.txt*** (MFW or XFW)<BR><BR>
and add (or replace) an entry as example below.

          Filetype: Flipper Animation Manifest
          Version: 1

          Name: RM_Spies
          Min butthurt: 0
          Max butthurt: 14
          Min level: 1
          Max level: 3
          Weight: 9
   Note that animation name entry must be the animation folder exact name.<BR>
   Edit the butthurt/level/weight values according to your needs and firmware.<BR>
   (You can also replace your existing manifest file by one I provided in this github...)
   
5. Reboot your Flipper (OS). And you're **DONE !**<BR>
Don't forget to select your asset pack if under Momentum / Xtreme.

<BR>

