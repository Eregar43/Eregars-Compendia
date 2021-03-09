![GitHub All Releases](https://img.shields.io/github/downloads/stschoelzel/My-Shared-Compendia/total) 

# My Shared Compendia
A Foundry VTT module to share Data between worlds via compendia as explained by u/solfolango on r/FoundryVTT; [here](https://www.reddit.com/r/FoundryVTT/comments/fvw3c7/how_to_create_a_tiny_module_for_shared_content/ "here").

## Installation
Simply use the install module screen within the FoundryVTT setup

## Default Setup
This module comes with 8 Default compendia. One for each Type of Entity that is [supported by FoundryVTT](https://foundryvtt.com/article/compendium/ "supported by FoundryVTT") and one extra "Actors".
- My Actors ([Actor](https://foundryvtt.com/api/Actor.html "Actor"))
- My Monsters ([Actor](https://foundryvtt.com/api/Actor.html "Actor"))
- My Items ([Item](https://foundryvtt.com/api/Item.html "Item"))
- My Scenes ([Scene](https://foundryvtt.com/api/Scene.html "Scene"))
- My Journal Entrys ([JournalEntry](https://foundryvtt.com/api/JournalEntry.html "JournalEntry"))
- My Macros ([Macro](https://foundryvtt.com/api/Macro.html "Macro"))
- My Roll Tables ([RollTable](https://foundryvtt.com/api/RollTable.html "RollTable"))
- My Playlists ([Playlist](https://foundryvtt.com/api/Playlist.html "Playlist"))

## Customize
To change the default setup simple edit the module.json. All compendia are defined within the "packs" attribute beginning with line 10. 

Theres a sample for each possible compendium Entity - so start there.
Delete or change as you see fit and/or [fork](https://github.com/user/repository/fork) for your convenience.


### Classes, Feats or Features
There are no enteties for Classes, Feats, Features or anything more than the seven listed available in FoundryVTT. Best practices is to use the "[Item](https://foundryvtt.com/api/Item.html "Item")"  entity for those.

For Example:

    		{
    			"name": "feats",
    			"label": "My Feats",
    			"path": "packs/feats.db",
    			"entity": "Item"
    		},
    		{
    			"name": "classes",
    			"label": "My Classes",
    			"path": "packs/classes.db",
    			"entity": "Item"
    		},
    		{
    			"name": "class-features",
    			"label": "My Class Features",
    			"path": "packs/class-features.db",
    			"entity": "Item"
    		}



## Dependencies
There a no known Dependencies.
But, [Compendium Folders](https://github.com/earlSt1/vtt-compendium-folders "Compendium Folders") is highly recomended.

## Software Versions & Module and System Incompatibilities
- Tested on: FoundryVTT 0.7.9
- Module and System Incompatibilities: None known
- Tested systems: DND 5e and Blades in the Dark
