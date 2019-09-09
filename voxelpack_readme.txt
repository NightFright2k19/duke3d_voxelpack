
========================
Duke Nukem 3D Voxel Pack
========================

Version:      1.3
Release Date: Sep 9, 2019
Authors:      ReaperMan & Duke4.net Community


============================================================================================
ABOUT
============================================================================================

This pack provides voxel replacements for sprites in Duke Nukem 3D.
It is meant to be used with the EDuke32 port, but is also compatible with BuildGDX.


============================================================================================
HOW TO USE
============================================================================================

- EDuke32: Drop this file (duke3d_voxels.zip) into your EDuke32 "autoload" directory.
	   Be sure that the autoload option in the launcher is checked and voxels 
           are activated in the ingame menu (Options > Display Setup > Voxels).

- BuildGDX: Drop this file (duke3d_voxels.zip) into your "autoload" directory.
            Be sure that the autoload option in the launcher is checked.


============================================================================================
NOTES
============================================================================================

1) It does not make sense to use this pack in combination with Duke3D HRP since you
   should either use voxels or models, but not both at the same time. It is technically
   possible, but regarding style, the packs are not meant to be used together. 

2) All of the voxel pack must be contained in a zip file, if it is not inside of a 
   zipfile, EDuke32 will not run the voxel pack.

3) As of now, Polymer does not support voxels.

4) To activate voxel rotation:
	- EDuke32: Open eduke32.con and remove "//" from line "include scripts/rotation.con"
	- BuildGDX: Open dukegdx.def and remove "//" from line "include voxels/pickups_gdx.def"

5) To activate voxels for monsters:
	- EDuke32: Open duke3d_voxels.def and remove "//" from line "include voxels/monsters.def"
	- BuildGDX: Open dukegdx.def and remove "//" from line "include voxels/monsters.def"


============================================================================================
LINKS
============================================================================================

> Duke Nukem 3D Voxel Pack thread:
  http://forums.duke4.net/topic/3322-duke-3d-voxel-pack

> Duke Nukem 3D Highres Pack:
  http://hrp.duke4.net

> EDuke32 port for Duke Nukem 3D:
  http://eduke32.com

> BuildGDX port:
  https://m210.duke4.net


============================================================================================
CREDITS
============================================================================================

Main Development:

> Voxel creation (except for instances listed below) & autoload file 
  ReaperMan

> All voxels based on work by 
  3D Realms


Contributions by:

> Borion (106)
     - 25 ................. Shrinker
     - 32 ................. Expander
     - 45 ................. Expander ammo
     - 56 ................. Scuba gear
     - 57 ................. Jetpack
     - 58 ................. Spacesuit
     - 100-115 ............ Atomic Health
     - 140/141 ............ Lever switch off/on
     - 142-145 ............ Nuke button
     - 563-565 ............ Water fountain
     - 569/615 ............ Toilet (+ broken version)
     - 571/573 ............ Urinal (+ broken version)
     - 606 ................ Spacesuit corpse
     - 669 ................ Vacuum cleaner
     - 685 ................ Stage light
     - 762 ................ Microphone
     - 765 ................ Vase
     - 911/939 ............ Cactus (+ stomp)
     - 913 ................ Maskwall2
     - 914 ................ Maskwall3
     - 915 ................ Gate
     - 916 ................ Fire extinguisher
     - 920 ................ Chain
     - 937 ................ "Forbidden Videos & Books" sign
     - 951 ................ Box
     - 961 ................ "Exit" sign
     - 962 ................ Fence
     - 981 ................ Hydrant
     - 990 ................ Tires
     - 1008 ............... Neon5 sign
     - 1025 ............... Bottle7 (plant)
     - 1046 ............... "Arcade" sign
     - 1061/1078 .......... Double spotlight (+ broken version)
     - 1062/1063 .......... Rubber can
     - 1075 ............... Painting #1
     - 1076 ............... Painting #2
     - 1079-1081 .......... Oozefilter
     - 1111/1112 .......... Handswitch
     - 1142/1143 .......... "Bighole" switch
     - 1172 ............... "Secured Area" sign
     - 1210 ............... "Guilty!" sign
     - 1211 ............... "Innocent?" sign
     - 1232 ............... Trash can
     - 1240-1243 .......... Fire barrel
     - 1247 ............... C-9 cannister
     - 1650-1653 .......... Mortar
     - 1880 ............... Sentry drone
     - 1975 ............... Pigcop tank
     - 2350/2355/2360 ..... Gun turret
     - 4360 ............... Gunpowder barrel
     - 4367 ............... Hatrack
     - 4372 ............... coffee machine
     - 4429 ............... Metal fence
     - 4438 ............... Mug
     - 4440 ............... Donuts
     - 4454 ............... Deskphone
     - 4483 ............... Broken switch #1
     - 4495 ............... "Wet Floor" sign
     - 4576 ............... Shopping cart
     - 4580-4582 .......... Barrels
     - 4885 ............... Driver wheel
     - 4891 ............... "We Store Your Crap" sign
     - 4954 ............... Broken switch #2
     - 4956 ............... "Funny Boner Comedy Club" sign

> DotK3D (22)
     - 561 ................ Soap
     - 572/991 ............ Shower part
     - 716 ................ "Please Wait" sign
     - 779 ................ Sushi plate eye
     - 860/861 ............ Powerswitch1 off/on
     - 864/865 ............ Powerswitch2 off/on
     - 904 ................ Wooden horse
     - 909 ................ Tree trunk
     - 954 ................ Cocktail glass
     - 977 ................ Pole
     - 978 ................ Traffic cone
     - 979 ................ Hanglight
     - 1006 ............... Bar stool
     - 1009-1011 .......... Neon5 sign
     - 1060/1067 .......... Clock (intact & broken)
     - 1069 ............... Plug
     - 4373 ............... Cups

> mxrtxn (16)
     - 584 ................ Sensor
     - 621 ................ Security camera
     - 670 ................ Running water tap
     - 1014 ............... Bottle
     - 1238 ............... Metal barrel
     - 4569 ............... Burger box
     - 4370 ............... Desk lamp
     - 4371 ............... Police shield
     - 4426 ............... Bowling pin
     - 4540-4542 .......... Foodobject11-13
     - 4546-4548 .......... Foodobject17-19
     - 4589 ............... Warning sign

> Shodanbot (5)
     - 138/139 ............ Slideswitch
     - 1122/1123 .......... Flipswitch
     - 4464 ............... Mace

> Striker (1)
     - 1037 ............... Table


Special thanks to:

> Hendricks266
> Phredreeke (World Tour maphacks)
> Scott_AW
> Wolfe 
> The whole Duke4.net community 

and:

> 3D Realms
  For that portable medkit :)


============================================================================================
CHANGELOG
============================================================================================

Version 1.3 (Sep 9, 2019)
-------------------------
> Added:
     + Support for BuildGDX via dukegdx.def
     + Monsters: 1880 (Sentry drone), 1975 (Pigcop tank), 2350 (Gun turret)
     + Pickups: 25 (Shrinker), 32 (Expander), 45 (Expander ammo), 56 (scuba gear), 57 (jetpack),
                100-115 (Atomic Health)
     + Projectiles: 1650-1653 (mortar)
     + Props: 58 (spacesuit), 563-565 (water fountain), 569/615 (toilet), 571/573 (urinal), 
              584 (sensor), 606 (spacesuit corpse), 669 (vacuum cleaner), 685 (stage light), 
              762 (mike), 765 (vase), 911/939 (cactus + stomp), 913 (maskwall2), 914 (maskwall3), 
              915 (gate), 916 (fire extinguisher), 920 (chain), 951 (box), 962 (fence), 
              981 (hydrant), 990 (tires), 1014 (bottle), 1025 (bottle7), 1061/1078 (double spotlight),
              1062/1063 (rubber can), 1075/1076 (painting #1/2), 1079-1081 (oozefilter), 
              1232 (trash can), 1238 (metal barrel), 1240-1243 (firebarrel), 1247 (C-9 can), 
              4360 (gunpowder barrel), 4367 (hatrack), 4370 (desk lamp), 4371 (police shield), 
              4372 (coffee machine), 4426 (bowling pin), 4429 (fence), 4438 (mug), 4440 (donuts), 
              4454 (deskphone), 4464 (mace), 4495 ("Wet Floor" sign), 4576 (shopping cart), 
              4580-4582 (barrels), 4589 (warning sign), 4885 (driver wheel)
     + Signs: 937 ("Forbidden Videos & Books"), 961 ("Exit"), 1008 (neon4), 1046 ("Arcade"), 
              1172 ("Secured Area"), 1210 ("Guilty!"), 1211 ("Innocent?"), 4891 ("We Store Your Crap"),
              4956 ("Funny Boner Comedy Club")
     + Switches: 138/139 (slideswitch), 140/141 (leverswitch), 142-145 (nuke button), 
                 1111/1112 (handswitch), 1122/1123 (flipswitch), 1142/1143 (bighole switch), 
                 4483 (broken switch #1), 4954 (broken switch #2)

> Updated:
     + Maphacks: Updated from latest Duke3D HRP SVN (r710)
     + duke3d.def: Option to undefine HRP models (only when using VP with HRP)
     + eduke.con: Voxel rotation deactivated by default
     + rotation.con: 4 useless cases (AMMOBOX, AMMOLOTS, HEALTHBOX, INVENTORYBOX) removed
     + pickups.def: Corrected animtilerange for HoloDuke


Version 1.21 (Mar 24, 2018)
---------------------------
> Added:
     + Maphacks: World Tour maphacks (by Phredreeke)
     + Props: 4540 (burger/foodobject11), 4541 (burger/foodobject12), 
              4542 (burger/foodobject13)


Version 1.2 (Mar 8, 2018)
-------------------------
> Added:
     + Props: 561 (soap), 572/991 (shower part), 716 ("Please wait"),
              909 (tree trunk), 979 (hanglight), 1009-1011 (neon5), 
              1037 (table), 4373 (cups), 4546 (empty fries box/foodobject17), 
              4547 (full fries box/foodobject18), 4548 (coke/foodobject19), 
              4549 (burger box)
     + Switches: 864/865 (powerswitch2 off/on)

> Updated:
     + Maphacks from latest Duke3D HRP SVN (r699)
     + Props: 1069 (plug)

> Code: 
     + eduke.con: Fixed warning for action HOLODUKE_FRAMES
     + animation.con: Contains animation code for HoloDuke and Freezer ammo
     + rotation.con: Voxel rotation code by Hendricks266 (can be deactivated in eduke.con)

> Other:
     + Voxel folder structure changed (removed "sprites" subdir and sprites.def)


Version 1.1 (Dec 24, 2014) 
--------------------------
> Added:
     + Pickups: Freezer, Freezer ammo, Holoduke, Expander ammo, Boots
     + Props: Bar stool, clock, traffic cone, roadblock, sushi plate eye, 
              pole, cocktail glass, security camera, faucet2, several 
               liquor/beer bottles
     + Switches: 7 switches (16 voxels total)
     + Maphacks for "Duke It Out In D.C."

> Updated:
     + Maphacks for original Duke3D episodes (from latest Duke3D HRP SVN)
     + duke3d_voxel.def: Updated tint defs (from latest Duke3D HRP SVN)

> WIP (not included with this release yet): 
     + Pickups: Shrinker, scuba gear, jetpack
     + Props: More bottles and switches 


Version 1.0 (Feb 12, 2012)
--------------------------
> Includes voxel replacements for
     + Pickups: 21 (pistol), 22 (chaingun), 23 (RPG), 26 (pipebomb), 27 (tripbomb), 
                28 (shotgun), 29 (Devastator), 40 (pistol ammo), 41 (chaingun ammo),
                42 (Devastator ammo), 44 (RPG ammo), 46 (Shrinker crystal), 
                47 (pipebomb box), 49 (shotgun ammo), 51 (health +10), 52 (health +30),
                53 (medkit), 54 (armor), 55 (steroids), 59 (nightvision goggles), 
                60 (keycard)
     + Props: 547 (faucet), 595 (grate1), 596 (bgrate2), 901 (stripeball), 902 (queball),
              1051 (dryer), 1052 (towel dispenser), 1053 (toilet paper), 1069 (plug)
     + Switches: 130/131 (access switch red/green), 132/133 (slotdoor red/green),
                 134/135 (lightswitch red/green), 162/163 (dipswitch red/green),
                 164/165 (dipswitch2 red/green), 170/171 (access switch #2 red/green),
                 712/713 (lightswitch down/up)
         