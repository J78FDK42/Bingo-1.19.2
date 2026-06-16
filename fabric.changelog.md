# Changelog
===============

All notable changes to this project will be documented in this file.


## [Unreleased] - TBD

### Added 

+ Official release file for Minecraft version 1.19.2 


## [0.2.0] - 2026-06-15 : Beta v2 Update!

### Added

+ Bingo 0.2.0 for Minecraft version 1.19.2
+ Bingo Game Screens
+ Bingo Loot datapack
+ Bingo Collectibles datapacks
+ Bingo language translations

#### Files

##### Core Game Files 

+ Bingo game file
+ Bingo card file
+ Bingo client/server save files
+ Bingo networking files
+ Bingo screen files
+ Bingo key binding file
+ Bingo commands file

##### Collectibles Datapacks

+ Custom collectibles easy peaceful datapack
+ Custom collectibles easy survival datapack
+ Custom collectibles medium peaceful datapack
+ Custom collectibles medium survival datapack
+ Custom collectibles hard survival datapack

Download Peaceful Easy Datapack: [collectibles_peaceful_easy_datapack.zip](https://github.com/J78FDK42/Bingo/blob/Bingo-0.2.0/collectibles_peaceful_easy_datapack.zip)
Download Survival Easy Datapack: [collectibles_survival_easy_datapack.zip](https://github.com/J78FDK42/Bingo/blob/Bingo-0.2.0/collectibles_survival_easy_datapack.zip)
Download Peaceful Medium Datapack: [collectibles_peaceful_medium_datapack.zip](https://github.com/J78FDK42/Bingo/blob/Bingo-0.2.0/collectibles_peaceful_medium_datapack.zip)
Download Survival Medium Datapack: [collectibles_survival_medium_datapack.zip](https://github.com/J78FDK42/Bingo/blob/Bingo-0.2.0/collectibles_survival_medium_datapack.zip)
Download Survival Hard Datapack: [collectibles_survival_hard_datapack.zip](https://github.com/J78FDK42/Bingo/blob/Bingo-0.2.0/collectibles_survival_hard_datapack.zip)

##### Game Loot Tables

+ Loot table files:
	* data/bingo/loot_tables/square.json
	* data/bingo/loot_tables/winner.json

Download Loot Tables: [BingoLoot.zip](https://github.com/J78FDK42/Bingo/blob/Bingo-0.2.0/BingoLoot.zip)

##### Language Translation Specification

+ Bingo English version language file
+ Bingo French version language file

Download Language Specification: [en_us.json](https://github.com/J78FDK42/Bingo/blob/Bingo-0.2.0/en_us.json)

#### Minecraft GUIs
+ Bingo Card screen
+ Bingo Winners screen
+ Bingo Start screen
 
##### Start Screen 

###### Main Tab
+ Game button
+ Options button
+ Teams button
+ Start/Stop button

###### Game Tab
+ Bingo button (standard bingo)
+ Blackout button (all squares bingo)
+ Twenty button (20 squares or best, no bingo)

###### Options Tab
+ Unlocks button 
+ Cards button
+ Progress button

###### Unlocks Tab
+ Recipes button
+ Advancements button

###### Recipes Tab
+ Vanilla checkbox - include/exclude vanilla recipes (all recipes with id of "minecraft")
+ Modded checkbox - include/exclude modded recipes (all recipes without id of "minecraft")
+ Custom checkbox - include/exclude custom recipes (all recipes with id provided by user)

###### Advancements Tab
+ Vanilla checkbox - include/exclude vanilla advancements (all advancements with id of "minecraft")
+ Modded checkbox - include/exclude modded advancements (all advancements without id of "minecraft")
+ Custom checkbox - include/exclude custom advancements (all advancements with id provided by user)

###### Card Options Tab
+ Personal toggle button - All players have individual randomized cards
+ Team toggle button - All players on the same team have the same randomized card
+ Global toggle button - All players have the same randomized card

###### Progress Options Tab
+ Personal toggle button - Squares unlock for each individual player
+ Team toggle button - Squares unlock for each player on the same team (except neutral)
+ Global toggle button - Squares unlock for all players in the session
+ Loot Generation checkbox - Loot is Generated for square and game completion using the bingo loot table

###### Teams Tab (optional)
+ Team Neutral toggle button (no team)
+ Team Red toggle button 
+ Team Blue toggle button 

#### Key Bindings
+ View Bingo card key `'o'`
+ View Start and Config key `'b'`

#### Minecraft item
`bingo:bingo_card`
+ right click / view card

#### Minecraft Commands

+ `bingo start` starts the game
+ `bingo stop` cancels any game in progress
+ `bingo reset` same as `bingo stop` to cancel a game in progress
+ `bingo start` starts the game for all active players
+ `bingo players` lists all active players in the session
+ `bingo add -player- red|blue` adds the player to the list of active team players
+ `bingo join red|blue` adds the player to the list of active team players
+ `bingo quit team` leaves the current team and joins the neutral team
+ `bingo toggle loot` toggles game loot generation on or off
+ `bingo game` displays the current game type


[0.2.0]: https://github.com/J78FDK42/Bingo-1.19.2/blob/Version-0.2.0/bingo-0.2.0-fabric-1.19.2.jar
