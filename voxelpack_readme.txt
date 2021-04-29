
========================
Duke Nukem 3D Voxel Pack
========================

Version:      2.0 (Release Candidate #2)
Release Date: Apr 29, 2021
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

> Borion (191)
     - 25 ................. Shrinker
     - 32 ................. Expander
     - 45 ................. Expander ammo
     - 56 ................. Scuba gear
     - 57 ................. Jetpack
     - 58 ................. Spacesuit
     - 100-115 ............ Atomic Health
     - 140/141 ............ Lever switch off/on
     - 142-145 ............ Nuke button
     - 479 ................ Antenna dish
     - 480 ................ Observatory
     - 551-554 ............ Lightdome
     - 556-557/559 ........ Armchair (+ broken version)
     - 563-565 ............ Water fountain
     - 569/615 ............ Toilet (+ broken version)
     - 571/573 ............ Urinal (+ broken version)
     - 574/670/671 ........ Faucet
     - 606 ................ Spacesuit corpse
     - 607/608 ............ Antenna
     - 669 ................ Vacuum cleaner
     - 558/675-677 ........ Slimer egg
     - 678 ................ Scale
     - 680-684 ............ Chair3
     - 685 ................ Stage light
     - 689 ................ IV unit
     - 694 ................ Pot1
     - 695 ................ Pot2
     - 697 ................ Pot3
     - 698 ................ Sushi plate
     - 728 ................ "Federal Loan and Trust" sign
     - 753/869 ............ Geisha
     - 762 ................ Microphone
     - 765 ................ Vase
     - 908 ................ Tree1
     - 910 ................ Tree2
     - 911/939 ............ Cactus (+ stomp)
     - 913 ................ Maskwall2
     - 914 ................ Maskwall3
     - 915 ................ Gate
     - 916 ................ Fire extinguisher
     - 917 ................ Fire alarm
     - 918 ................ Meter3
     - 919 ................ Meter2
     - 920 ................ Chain
     - 925 ................ Neon1
     - 926 ................ Neon2
     - 937 ................ "Forbidden Videos & Books" sign
     - 938 ................ "San Andreas Fault" sign
     - 951 ................ Box
     - 954 ................ Bottle1
     - 955 ................ Bottle2
     - 956 ................ Bottle3
     - 957 ................ Bottle4
     - 961 ................ "Exit" sign
     - 962 ................ Fence
     - 969/1003 ........... Hydroplant (+ broken version)
     - 981/950 ............ Hydrant (+ broken version)
     - 990 ................ Tires
     - 1008 ............... Neon5 sign
     - 1012 ............... Bottle5
     - 1013 ............... Bottle6
     - 1025 ............... Bottle7 (plant)
     - 1045 ............... Donuts
     - 1046 ............... "Arcade" sign
     - 1048 ............... Two cables
     - 1049 ............... Electric meter
     - 1061/1078 .......... Double spotlight (+ broken version)
     - 1062/1063 .......... Rubber can
     - 1073 ............... Life buoy
     - 1075 ............... Painting #1
     - 1076 ............... Painting #2
     - 1079-1081 .......... Oozefilter
     - 1111/1112 .......... Handswitch
     - 1142/1143 .......... "Bighole" switch
     - 1158 ............... Bottle11
     - 1160 ............... Bottle13
     - 1164-1166 .......... Bottle17-19
     - 1172 ............... "Secured Area" sign
     - 1210 ............... "Guilty!" sign
     - 1211 ............... "Innocent?" sign
     - 1227-1230 .......... Nuke barrel
     - 1232 ............... Trash can
     - 1240-1243 .......... Fire barrel
     - 1247 ............... C-9 cannister
     - 1337-1338 .......... Helicopter (running)
     - 1340-1342 .......... Helicopter debris
     - 1343 ............... Broken wheel
     - 1344 ............... Propeller
     - 1345 ............... Helicopter (parking)
     - 1346 ............... Helicopter (crashing)
     - 1353 ............... Space Marine
     - 1390-1393 .......... Fire vase
     - 1650-1653 .......... Mortar
     - 1880 ............... Sentry drone
     - 1975 ............... Pigcop tank
     - 2350/2355/2360 ..... Gun turret
     - 2566 ............... Tripbomb (mounted)
     - 4360 ............... Gunpowder barrel
     - 4367 ............... Hatrack
     - 4372 ............... coffee machine
     - 4377 ............... Police light pole
     - 4429 ............... Metal fence
     - 4438 ............... Mug
     - 4440 ............... Donuts
     - 4443 ............... US flag
     - 4444 ............... VHS camera
     - 4454 ............... Deskphone
     - 4458/4459 .......... Gumball machine
     - 4483 ............... Broken switch #1
     - 4495 ............... "Wet Floor" sign
     - 4524 ............... "Steed" hooks
     - 4536-4539 .......... Foodobject7-10
     - 4576 ............... Shopping cart
     - 4580-4582 .......... Barrels
     - 4885 ............... Driver wheel
     - 4891 ............... "We Store Your Crap" sign
     - 4930 ............... "E Pluribus Nukem" sign
     - 4943 ............... Hung jury
     - 4954 ............... Broken switch #2
     - 4956 ............... "Funny Boner Comedy Club" sign

> DJP (2)
     - 691 ................ Cleaver
     - 692 ................ Knife

> DotK3D (22)
     - 561 ................ Soap
     - 572/991 ............ Shower part
     - 716 ................ "Please Wait" sign
     - 779 ................ Sushi plate eye
     - 860/861 ............ Powerswitch1 off/on
     - 864/865 ............ Powerswitch2 off/on
     - 904/1026 ........... Wooden horse
     - 909 ................ Tree trunk
     - 977 ................ Pole
     - 978 ................ Traffic cone
     - 979 ................ Hanglight
     - 1006 ............... Bar stool
     - 1009-1011 .......... Neon5 sign
     - 1060/1067 .......... Clock (intact & broken)
     - 1069 ............... Plug
     - 4373 ............... Cups

> Dzierzan (75)
     - 160 ................ Door shock
     - 487 ................ Space shuttle
     - 489 ................ Satellite
     - 517 ................ Gas tank
     - 536/537 ............ Small pipe
     - 543 ................ Panel
     - 544 ................ Connection
     - 555 ................ Small valve
     - 570 ................ Soap
     - 572/991 ............ Shower part (based on DotK3D's voxel)
     - 578 ................ Reactor
     - 602 ................ Solar panel
     - 610 ................ Pipe
     - 660 ................ Water drop
     - 976 ................ Air vent
     - 993 ................ Damaged pole
     - 994-996 ............ Pipes
     - 997/1005/1260 ...... Broken pipes
     - 998/999 ............ Parking meter
     - 1014 ............... Bottle (based on mxrtxn's voxel)
     - 1022-1023 .......... Green goo
     - 1026 ............... Wooden horse fallen (based on DotK3D's voxel)
     - 1037 ............... Table (remake, original by Striker)
     - 1038 ............... Horizontal pipe
     - 1157 ............... Money jar
     - 1238 ............... Metal barrel
     - 1267 ............... Rat
     - 1810 ............... Cannon
     - 1817 ............... Cannonball
     - 1818 ............... Cannonballs
     - 2200 ............... Poo
     - 3190 ............... Red marker
     - 3200 ............... Yellow marker
     - 3210 ............... Green marker
     - 3400 ............... "Duf Beer" blimp
     - 3418 ............... Side mirror
     - 4359 ............... Target
     - 4361 ............... Duck
     - 4363 ............... Knife
     - 4374/4375 .......... Gavel
     - 4386 ............... Pipe
     - 4407/4408 .......... Annoying mouse
     - 4413 ............... Mail bag
     - 4416/4417 .......... Side mirror
     - 4419 ............... Broken pipebomb
     - 4441/4442/4473 ..... "McClain"/"Callahan"/"Dredd" name tags
     - 4446 ............... Prison ball
     - 4457 ............... Rope
     - 4465 ............... Generic pole
     - 4496 ............... Broom
     - 4533 ............... Kitchen object
     - 4549 ............... Burger wrapper (Foodobject20)
     - 4550 ............... Red lamp
     - 4552 ............... Worms can
     - 4567 ............... Icicles
     - 4583 ............... Pipe
     - 4585 ............... Valve
     - 4586/4587 .......... Thin pipe
     - 4946 ............... Baseball bat
     - 5384 ............... Lamp
     - 5435 ............... Mailbox
     - 5436 ............... Lamp
     - 5675 ............... Bollard
     - 5679 ............... Bridge lamp #1
     - 5680 ............... Bridge lamp #2

> mxrtxn (40)
     - 584 ................ Sensor
     - 621 ................ Security camera
     - 1014 ............... Bottle
     - 4569 ............... Burger box
     - 4370 ............... Desk lamp
     - 4371 ............... Police shield
     - 4426 ............... Bowling pin
     - 4540-4542 .......... Foodobject11-13
     - 4546-4548 .......... Foodobject17-19
     - 4589 ............... Warning sign

     Caribbean:
     - 21 ................. Water pistol
     - 22 ................. Triple poison shooter
     - 23 ................. Coconut launcher
     - 24 ................. Ice crusher
     - 25 ................. Voodoo ring
     - 27 ................. Voodoo trip bomb
     - 28 ................. Super Soak'em
     - 37-39 .............. Ice crusher ammo
     - 40 ................. Water pistol ammo
     - 41 ................. Triple poison shooter ammo
     - 49 ................. Super Soak'em ammo
     - 51 ................. Single banana
     - 52 ................. Bunch of bananas
     - 53 ................. Crate of bananas
     - 54 ................. Suntan lotion
     - 55 ................. Hot sauce
     - 56 ................. Snorkle
     - 59 ................. Sunglasses
     - 60 ................. Credit card
     - 955 ................ Blue drink
     - 956 ................ Cocktail
     - 3695 ............... Parasol
     - 3791 ............... Cooling box
     - 3792 ............... Radio

> pavigna (1)
     - 4387 ............... Dukeburger table

> Shodanbot (5)
     - 138/139 ............ Slideswitch
     - 1122/1123 .......... Flipswitch
     - 4464 ............... Mace
     
> Striker (1)
     - 1037 ............... Table (original)


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

Version 2.0 RC2 (Apr 29, 2021)
------------------------------
> Added:
     + Props: 160 (door shock), 479 (antenna dish), 489 (satellite), 517 (gas tank), 536/537 (small pipe), 
              555 (small valve), 570 (soap), 578 (reactor), 602 (solar panel), 610 (pipe), 660 (water drop), 
              976 (air vent), 993 (damaged pole), 998/999 (parking meter), 1022-1023 (green goo), 1026 (wooden horse fallen), 
              1038 (horizontal pipe), 1157 (money jar), 1337-1338 (helicopter running), 1340-1342 (helicopter debris), 
              1343 (broken wheel), 1344 (propeller), 1345 (helicopter parking), 1346 (helicopter crashing),
              3400 ("Duf Beer" blimp), 3418 (side mirror), 4359 (target), 4361 (duck), 4363 (knife), 4374/4375 (gavel),
              4386 (pipe), 4413 (mail bag), 4416/4417 (side mirror), 4419 (broken pipebomb), 
              4441/4442/4473 (McClain/Callahan/Dredd name tags), 4446 (prison ball), 4465 (generic pole), 
              4533 (kitchen object), 4549 (burger wrapper), 4567 (icicles), 4583 (pipe), 4585 (valve), 4586/4587 (thin pipe), 
              4943 (hung jury), 4946 (baseball bat), 5384 (lamp), 5435 (mailbox), 5436 (lamp), 5675 (bollard), 
              5679 (bridge lamp #1), 5680 (bridge lamp #2)

> Updated:
     + World Tour maphacks fixed (references to non-existing files corrected)
     + Maphacks: E2L3 (#602 solar panel), E3L1 (#753 geisha statue), E3L5 (#1346 helicopter),
                 E3L7 (#3418 sidemirror), E4L2 (#4567 icicles), E4L5 (#4441/4442/4473 name tags, #4444 tripod cam),
                 E4L6 (#3418 sidemirror)
     + Monsters: Turret (#2350) activated in monsters.def
     + Props: 487 (space shuttle), 572/991 (shower part), 1014 (bottle), 1037 (table), 1238 (metal barrel)


Version 2.0 RC1 (Dec 3, 2020)
-----------------------------
> Added:
     + Support for BuildGDX via dukegdx.def
     + Misc: 3190/3200/3210 (red/yellow/green marker)
     + Monsters: 558/675 (Slimer egg), 1880 (Sentry drone), 1975 (Pigcop tank), 2350 (Gun turret)
     + Pickups: 25 (Shrinker), 32 (Expander), 45 (Expander ammo), 56 (scuba gear), 57 (jetpack),
                100-115 (Atomic Health)
     + Projectiles: 1650-1653 (mortar), 2566 (tripbomb)
     + Props: 58 (spacesuit), 480 (observatory), 487 (space shuttle), 543 (panel), 544 (connection), 551-554 (lightdome), 
              556-557/559 (armchair), 563-565 (water fountain), 569/615 (toilet), 571/573 (urinal), 584 (sensor), 
              606 (spacesuit corpse), 607/608 (antenna), 669 (vacuum cleaner), 671 (faucet3), 678 (scale), 680-684 (chair3), 
              685 (stage light), 689 (IV unit), 691 (cleaver), 692 (knife), 694 (pot1), 695 (pot2), 697 (pot3), 698 (sushi plate), 
              753/869 (geisha), 762 (mike), 765 (vase), 908 (tree1), 910 (tree2), 911/939 (cactus + stomp), 913 (maskwall2), 
              914 (maskwall3), 915 (gate), 916 (fire extinguisher), 917 (fire alarm), 918 (meter3), 919 (meter2), 
              920 (chain), 925 (neon1), 926 (neon2), 994-996 (pipes), 951 (box), 955-957 (bottle2-4), 962 (fence),
              969/1003 (hydroplant), 981/950 (hydrant), 990 (tires), 997/1005/1260 (broken pipes), 1012 (bottle5), 
              1013 (bottle6), 1014 (bottle), 1025 (bottle7), 1045 (donuts), 1048 (two cables), 1049 (electric meter), 
              1061/1078 (double spotlight), 1062/1063 (rubber can), 1073 (life buoy), 1075/1076 (painting #1/2), 
              1079-1081 (oozefilter), 1158 (bottle11), 1160 (bottle13), 1164-1166 (bottle17-19), 1227-1230 (nuke barrel),
              1232 (trash can), 1238 (metal barrel), 1240-1243 (firebarrel), 1247 (C-9 can), 1267 (rat), 1353 (Space Marine), 
              1390-1393 (fire vase), 1810 (cannon), 1817/1818 (cannonballs), 2200 (poo), 4360 (gunpowder barrel), 
              4367 (hatrack), 4370 (desk lamp), 4371 (police shield), 4372 (coffee machine), 4377 (police light pole), 
              4387 (Dukeburger table), 4426 (bowling pin), 4429 (fence), 4438 (mug), 4440 (donuts), 4443 (US flag), 
              4444 (VHS camera), 4454 (deskphone), 4457 (rope), 4458/4459 (gumball machine), 4464 (mace), 
              4495 ("Wet Floor" sign), 4496 (broom), 4524 ("Steed" hooks), 4536-4539 (foodobject7-10), 4550 (red lamp), 
              4552 (worms can), 4576 (shopping cart), 4580-4582 (barrels), 4589 (warning sign), 4885 (driver wheel)
     + Signs: 728 ("Federal Loan and Trust"), 937 ("Forbidden Videos & Books"), 938 ("San Andreas Fault"), 
              961 ("Exit"), 1007 (neon3), 1008 (neon4), 1046 ("Arcade"), 1172 ("Secured Area"), 
              1210 ("Guilty!"), 1211 ("Innocent?"), 4891 ("We Store Your Crap"), 4930 ("E Pluribus Nukem"), 
              4956 ("Funny Boner Comedy Club")
     + Switches: 138/139 (slideswitch), 140/141 (leverswitch), 142-145 (nuke button), 
                 1111/1112 (handswitch), 1122/1123 (flipswitch), 1142/1143 (bighole switch), 
                 4483 (broken switch #1), 4954 (broken switch #2)
     + Vacation: 21 (water pistol), 22 (triple poison shooter), 23 (coconut launcher), 24 (ice crusher), 25 (voodoo ring), 
                 27 (voodoo trip bomb), 28 (Super Soak'em), 37-39 (ice crusher ammo), 40 (water pistol ammo), 
                 41 (triple poison shooter ammo), 49 (Super Soak'em ammo), 51 (banana), 52 (bunch of bananas),
                 53 (crate of bananas), 54 (suntan lotion), 55 (hot sauce), 56 (snorkle), 59 (sunglasses), 60 (credit card), 
                 955 (blue drink), 956 (cocktail), 3695 (parasol), 3791 (cooling box), 3792 (radio)

> Updated:
     + Props: 574/670 (faucet1+2), 954 (bottle1)
     + Voxel orientations: 40, 45, 670, 753, 869, 1008, 4438, 4443, 4444, 4546, 4547, 4548, 4569, 4576
     + Maphacks: Based on Duke3D HRP SVN r727; 
                 E1L1/NW2 (#925 / neon1), 
                 E2L8 (#521, 594, 596-598 / dead astronaut),
                 E3L4 (#678 / scale), 
                 E3L7 (#607 / antenna), 
                 E4L2 (#476-478 / foodobject18 + #572 / wormscan), 
                 E4L5 (#4377 / policelightpole), 
                 E4L8 (#4443 / flag)
                 DUKEDC4 (#487 / shuttle)
     + duke3d.def: Option to undefine HRP models (only when using VP with HRP)
     + eduke.con: Voxel rotation deactivated by default
     + rotation.con: 4 useless cases (AMMOBOX, AMMOLOTS, HEALTHBOX, INVENTORYBOX) removed
     + pickups.def: Corrected animtilerange for HoloDuke

> Removed:
    + freezeammo.con, holoduke.con (contain deprecated code, no longer needed)


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
     + Props: 574 (faucet), 595 (grate1), 596 (bgrate2), 901 (stripeball), 902 (queball),
              1051 (dryer), 1052 (towel dispenser), 1053 (toilet paper), 1069 (plug)
     + Switches: 130/131 (access switch red/green), 132/133 (slotdoor red/green),
                 134/135 (lightswitch red/green), 162/163 (dipswitch red/green),
                 164/165 (dipswitch2 red/green), 170/171 (access switch #2 red/green),
                 712/713 (lightswitch down/up)
         
