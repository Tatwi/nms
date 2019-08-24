# My No Man's Sky Stuff
This repository contains my personal game play adjustments, custom graphic/3D/audio files, and reference material for version 1.77 of No Man's Sky. It is compatible with the GOG.com patch 44840_Main_26826; Other versions of the game are not intended to be used.

## Game Balance
I started  playing NMS in 2019 durring the [version 1.77 update](https://www.nomanssky.com/release-log/), with a about a 50/50 split between Normal and Survival modes (in single player). While I truly love the game, I've come to the conclusion that it is both amazing and *amazingly easy*! After the first hour, "Survival Mode" ends up being "Tedious Resource Requirement Mode" - it's simply not any harder than Normal Mode at all once one can carry enough resources to recharge the protections and one has a few upgrade modules. Seriously, in 70 hours of survival game play, I died 3 times: twice when I blew myself up with the plasma cannon while decorating my base (too many things are bound to the right mouse button, making it easy to accidentally fire your secondary weapon), and once when I ended a rocket boots jump at the top of very deep hole. Yeah, the game is crazy easy, but it's also very fun!  

With that in mind, I made a series of balance adjustments and misc customizations to make the game play experience be more of what I was expecting it to be when I bought the game. Use'em if ya like'm!  

For the record, I don't consider editing some existing values in the XML files provided with the game to be *real modding*, so I am not going to refer to these adjustments as "mods". [Legend of Hondo](https://github.com/Tatwi/legend-of-hondo) and [Rescue Girlies](https://github.com/Tatwi/RescueGirlies) are examples of what I consider to be *real modding*. Anyway, kudos to Hello Games for making so many values in the game as human-readable XML options. Creating a project in that manner takes a whole lot more effort than just putting the values in the C++ headers, but it also makes it quick and idiot proof to change the values in the compiled client.  

Packaged "mods" that are ready to use with the game are in the [releases](/releases) directory.  
  
## Balance Adjustments
The documentation for these adjustments can be found in the [game_balance](/game_balance) README file.

## Graphics, Models, Audio
If make any and I decide to share them, they will be in the [art](/art) directory. 

## Misc Preferences
**Camera Adustments** [camera](/camera)  
- Adjustments to the camera of the vehicles, making it less cumbersome to mine using the Roamer (buggy) and preventing the weapon/laser on all of the vehicles from resetting (thus moving off the target).  
- Disabled the white flash on camera transitions, as they gave me head aches and eye strain.

## Reference Material
Documentation specific to version 1.77 of the game can be found in the [reference](/reference) directory.

## License
GNU AFFERO GENERAL PUBLIC LICENSE Version 3, 19 November 2007 See the LICENSE file for copying / copyright details.

## Thanks
- [PSArc documentation](https://www.psdevwiki.com/ps3/PlayStation_archive_(PSARC)) covering the Playstation archive file format.
- monkeyman192 for the [MBIN Compiler](https://github.com/monkeyman192/MBINCompiler/).
- periander for [PSArcTool](https://github.com/periander/PSArcTool).
- tubocrisco for [NMS Modding Station](https://www.nexusmods.com/nomanssky/mods/320).
