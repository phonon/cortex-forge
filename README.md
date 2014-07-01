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
If you are adding the Cortex related mods:
 * Thrikodias's Cortex Expansion Project
 * Gatorkit (relies on Thrikodias's Content Expansion Project)
 * Thrikodias's Fantasy Mod

  these mods already include the Toolkit, so you only need to add this mod instead of the Cortex Toolkit.

2. Go to **Modules > Import** (F9) and import all *.galaxy into /Cortex in root (as in, these files should all
fall under the "Cortex" folder in the root of the import).
Import GameUIOverride.SC2Layout to also be in the /Cortex folder.
The basic imported file hierarchy should look something like the following:  
![](http://i.imgur.com/x18mUqB.jpg)

3. Go to **Modules > Triggers** (F6) and import trigger library CortexHelper.SC2Lib (right click the triggers list and use **Library > Import Library...**)  
The "Map Settings" file contains map variables that you can change.

4. Finally, adjust player properties:  
  * **Map > Player Properties** : Select Player 14 and set **Control** to Computer. You can enable as many other players as you want; in general you should select all Players 1-13 and set **Control** to User.  
  * **Map > Game Variants** (Optional) : Deselect the bottom-left box **Use Default Variants**. In the variants box, right click and select **Add**. You can adjust the properties in each tab as needed. If you add multiple variants, different variants can be hosted at the same time, which can help bypass afk lobby hosts or lobby campers.

5. **Test locally before you publish!** Obviously this isn't needed, but it's good to test your map before you publish onto Battle.net.
  
  
You can ask about any installation issues/questions on this official [Cortex forum board](http://cortexrp.com/forums/viewforum.php?f=8).


### Links ###
[**Cortex forums** ] (http://www.cortexrp.com/forums)  
[**SC2Mapster Page**] (http://www.sc2mapster.com/assets/cortex-toolkit/)  
[**Github Repository**] (https://github.com/xethyr/cortex-forge)  