![Header](Images/animationheader.gif)

Here are some custom animations I made for the Flipper Zero. All animations will be in theme categories for easy navigation* :

- [Rogue Master Themed](https://github.com/ATOMNFT/Flipper-Vault/tree/main/Animations/Rogue%20Master%20Themed) - Dedicated to Rogue Master
- [Hacker Themed](https://github.com/ATOMNFT/Flipper-Vault/tree/main/Animations/Hacker%20Themed) - Dedicated to the hacker in us all



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
          Min level: 0
          Max level: 30
          Weight: 8
		  <br>
   Note that animation name entry must be the animation folder exact name.<BR>
   Edit the butthurt/level/weight values according to your needs and firmware.<BR>
   (You can also replace your existing manifest file by one I provided in this github...)
   
5. Reboot your Flipper (OS). And you're **DONE !**<BR>
Don't forget to select your asset pack if under Momentum / Xtreme.

<BR>


<p align="left"> <img src="https://komarev.com/ghpvc/?username=atomnft&label=Profile%20views&color=0e75b6&style=flat" alt="atomnft" /> </p>
<p align="left"> <a href="https://twitter.com/a_t_o_m_nft" target="blank"><img src="https://img.shields.io/twitter/follow/a_t_o_m_nft?logo=twitter&style=for-the-badge" alt="a_t_o_m_nft" /></a> </p>

