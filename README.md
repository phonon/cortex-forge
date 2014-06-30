Cortex Forge Extensions
--------------------------------

------------------------------------------------------------------

##### Version: v1.2
##### License: GNU GENERAL PUBLIC LICENSE

------------------------------------------------------------------ 

> "Cortex is a roleplaying map for Starcraft II, Blizzard's latest real-time strategy game. In a roleplaying map, the players create their own storyline to go along with anything they create, and interact with other players to move the story forward through time. Because of the highly dynamic nature of roleplaying maps, Cortex focuses on making it so that you can do everything possible in-game that you would otherwise need the Galaxy Editor to make. You accomplish this highly customized creating through the use of specialized chat commands such as @spawn to create units." (Motive)

Cortex Toolkit is mod for Starcraft II that creates a sandbox environment that utilizes text commands to affect almost every aspect of gameplay. While this mod is primarily intended for roleplaying--players taking on different roles to collectively create a story--the sandbox created by Cortex can be used for anything from testing units, setting up scenes, or prototyping data for custom maps.

Cortex Forge Extensions are further additions to Cortex after v2.1. There were initially concerns about its addition to the main branch of the Cortex Engine, so the additions were considered extensions, and now the name "Forge" is well known among the Cortex community. Additions include saving/loading, user-defined blacklists, command caches on units, camera manipulation, ui, and various other features.


### Installation ###

1. Go to **File > Dependencies** and use "Add Other" to find and add "Cortex Toolkit" (published under Motive)
(If adding other Cortex related mods, namely Thrikodias's Mod or Gatorkit--these include the Toolkit, so one can just add this mod instead of the Cortex Toolkit)

2. Go to **Modules > Import** (F9) and import all *.galaxy into /Cortex in root (as in, these files should all
fall under the "Cortex" folder in the root of the import).
Import GameUIOverride.SC2Layout to be in the root (so not included under /Cortex)

3. Go to **Modules > Triggers** (F6) and import trigger library CortexHelper.SC2Lib (right click the triggers list and use Library > Import Library...

4. Finally, adjust player properties:  
**Map > Player Properties** : adjust these add needed, so long as Player 14 is a Computer  
**Map > Game Variants** : add a variant and adjust the properties as needed  

Further instructions can be found at: http://cortexrp.com/forums/viewtopic.php?f=8&t=1554
(note that this tutorial is rather outdated)


### Links ###
[**Cortex forums** ] (http://www.cortexrp.com/forums)  
[**SC2Mapster Page**] (http://www.sc2mapster.com/assets/cortex-toolkit/)  
[**Github Repository**] (https://github.com/xethyr/cortex-forge)  