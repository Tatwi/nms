# My No Man's Sky Stuff
This repo contains my personal game play balance adjustments and custom graphics, models, and audio files.  

## Game Balance
After playing the game for at least 150 hours since the [version 1.77 update](https://www.nomanssky.com/release-log/), with a about a 50/50 split between Normal and Survival modes (in single player), I've come to the conclusion that the game is both amazing and *amazingly easy*! After the first hour, "Survival Mode" ends up being "Tedious Resource Requirement Mode" - it's simply not any harder than Normal Mode at all once one can carry enough resources to recharge the protections and one has a few upgrade modules. Seriously, in 70 hours of survival game play, I died 3 times: twice when I blew myself up with the plasma cannon while decorating my base, once when I ended a rocket boots jump at the top of very deep hole. Yeah, the game is crazy easy, but it's also very fun!  

With that in mind, I made a series of balance adjustments (some to Normal Mode specifically) to make the game play experience be more of what I was expecting it to be when I bought the game earlier this year. These adjustments are in the [game_balance](/game_balance) directory. I'm sure they won't be to many people's liking, but I am sharing them here to show what can be done. Use'em if ya like'm!  

For the record, I don't consider editing some existing values in the XML files provided with the game to be *real modding*, so I am not going to refer to these adjustments as "mods". [Legend of Hondo](https://github.com/Tatwi/legend-of-hondo) and [Rescue Girlies](https://github.com/Tatwi/RescueGirlies) are examples of what I consider to be *real modding*. Anyway, kudos to Hello Games for making so many values in the game as human-readable XML options. Creating a project in that manner takes a whole lot more effort than just putting the values in the C++ headers, but it also makes it quick and idiot proof to change the values in the compiled client.  

Packaged "mods" that are ready to use with the game are in the [releases](/releases) directory. Check their file names for which version of the game I tested them to be compatible with. For example,  
  
**Tatwi.game_balance_2019-06-27_GOG-44840_Main_26826.pak**  
   
Means "my game balance adjustments, packaged on 2019-06-27, compatible with Good Old Games patch 44840_Main_26826 of version 1.77 of No Man's Sky".

## Graphics, Models, Audio
I am not sure that I want to release my *real mods* as "open source", because I've discovered over the years that very few people actually appreciate the time, effort, and talent that goes into making such content. However, if I do decide to release something, it will be in the [art](/art) directory. 

## License
GNU AFFERO GENERAL PUBLIC LICENSE Version 3, 19 November 2007 See the LICENSE file for copying / copyright details.

## Thanks
- [PSArc documentation](https://www.psdevwiki.com/ps3/PlayStation_archive_(PSARC)) covering the Playstation archive file format.
- monkeyman192 for the [MBIN Compiler](https://github.com/monkeyman192/MBINCompiler/).
- periander for [PSArcTool](https://github.com/periander/PSArcTool).
- tubocrisco for [NMS Modding Station](https://www.nexusmods.com/nomanssky/mods/320).