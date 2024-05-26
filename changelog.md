# Changelog
===============

All notable changes to this project will be documented in this file.


## [Unreleased] - TBD

### Added 

+ Official release file for Minecraft version 1.19.2


## [1.19.2-1.0.5b] - 2024-05-27
---------------

### Added 

+ Loot table files:
	* data/bingo/loot_tables/square.json
	* data/bingo/loot_tables/winner.json
+ Random loot is generated from the square.json loot table when a player completes a square
+ Random loot is generated from the winner.json loot table when a player wins the game
+ Minecraft command `bingo loot` toggles game loot generation on or off
+ Minecraft command `bingo kick -player-` removes a player from the game (requires op privileges)
+ Bingo config file option for Loot Generation
+ An Options button and page have been added to the Start GUI
+ Start GUI option for Loot Generation on the Progress page

### Changed

+ Players must join the game before the game is started
+ Start GUI displays stop once started or reset when game ends
+ Start GUI displays join or quit once joined
+ Advancements, Cards, and Progress settings have been moved to the Options page of the Start GUI
+ All translatable text has been changed to translatable text objects
+ System chat messages are sent once from only the caller
+ Advancement text parsing was expanded to work better with modpacks like FTB Skies
+ An error message is displayed if the game card is viewed when any of the settings have changed
+ Minecraft command `bingo players` displays an error message when no players have joined the game
+ Improved game board and play validation checks
+ Recipe Advancement option now works with both Vanilla and Custom options
+ Recipe Advancement option adds recipe advancements to Vanilla or Custom options or both
+ Recipe Advancement option by itself does not include any advancements, a Vanilla or Custom option must be selected
+ Easy Collectibles datapack has been expanded to include more items (100+ items!)
+ Medium Collectibles datapack has been expanded to include more items (100+ items!)
+ Hard Collectibles datapack has been expanded to include more items (100+ items!)

### Fixed

+ Scoring issue with Red vs. Blue team play
+ End game activation issue
+ Minecraft command `bingo joined` and `bingo join` multi-thread/multi-player issue
+ Minecraft command `bingo join red|blue` multi-thread/multi-player issue
+ Easy collectible Granite now displays and responds to granite
+ Hard Collectibles datapack has been expanded to include at least 24+ items (full board)


## [1.19.2-1.0.4b] - 2022-11-25
---------------

### Fixed

* issue with player join and new settings
* issue with generating team and global bingo cards
* issue with initial loading of validation data
* issue with game update after game ended

### Changed

* a player can now join a game in progress
* a new bingo card is generated only if the player does not already have one
* a player can switch teams, but only if the game has not yet started
* some of the collectibles advancements were moved or changed
* all collectibles datapacks are now archived in a single file

### Added

* Game Start and Config GUI
* Bingo card validation check for team progress
* Bingo card validation check for team bingo cards
* some new collectibles advancements were added


## [1.19.2-1.0.3b] - 2022-11-15
---------------

### Fixed

* issue loading custom advancements
* issue with blue team win trigger
* issue with advancement criteria for global/team progress

### Added

* custom collectibles easy datapack
* custom collectibles medium datapack
* custom collectibles hard datapack


## [1.19.2-1.0.2b] - 2022-11-11
---------------

### Fixed

* Minecraft command `bingo add -player-` adds the player only if the player is not already added to the game
* Player progress null square issue
* Player progress null card issue

### Changed

* Minecraft command `bingo add -player-` adds the player to the list of active players
* Minecraft command `bingo start` starts the game for all active players
* Minecraft command `bingo reset` renamed to `bingo stop` to cancel a game in progress

### Added

* Minecraft command `bingo add all` adds all players in the session to the list of active players
* Minecraft command `bingo start all` starts the game for all players in the session
* Minecraft command `bingo players` lists all active players in the session
* Minecraft command `bingo add -player- red|blue` adds the player to the list of active team players
* Minecraft command `bingo join` adds the player to the list of active players
* Minecraft command `bingo join red|blue` adds the player to the list of active team players
* Minecraft command `bingo quit` cancels the player's game in progress
* Bingo config files
	+ Team players use the same bingo card in the game
	+ Team player advancement is marked completed for all players on the team
    
### Removed

* Minecraft command `bingo restart`


## [1.19.2-1.0.1b] - 2022-11-07
---------------

### Fixed

* HUD display error
* Global progress option grants achievement to all players

### Added

* Game save state / load state
* Minecraft command `bingo add -player-`


## [1.19.2-1.0.0b] - 2022-10-28
---------------

### Added

#### Files

+ Bingo game files
+ Bingo networking files
+ Bingo utility files
+ Bingo GUI files
+ Bingo config files
	* Include recipe advancements in the game
	* Include vanilla advancements in the game
	* Include custom advancements in the game
	* All players use the same bingo card in the game
	* Any player advancement is marked completed for all players in the game
+ Assets
	* Bingo Card item model
	* Bingo Card item texture
	* Bingo Card screen texture
	* Winner screen texture

#### Minecraft GUI

+ Bingo card screen
+ Bingo winners screen
- Key Binding
View Bingo card key `'o'`

#### Minecraft Item

`bingo:bingo_card`
+ right click / view card

#### Minecraft Commands

+ `bingo start` 
	* Starts game
+ `bingo reset` 
	* Cancels any game in progress
+ `bingo restart` 
	* Restarts the game


[1.19.2-1.0.5b]: https://github.com/J78FDK42/Bingo-1.19.2/raw/Version-1.0b/bingo-1.19.2-1.0.5b.jar
[1.19.2-1.0.4b]: https://github.com/J78FDK42/Bingo-1.19.2/raw/Version-1.0b/bingo-1.19.2-1.0.4b.jar
[1.19.2-1.0.3b]: https://github.com/J78FDK42/Bingo-1.19.2/raw/Version-1.0b/bingo-1.19.2-1.0.3b.jar
[1.19.2-1.0.2b]: https://github.com/J78FDK42/Bingo-1.19.2/raw/Version-1.0b/bingo-1.19.2-1.0.2b.jar
[1.19.2-1.0.1b]: https://github.com/J78FDK42/Bingo-1.19.2/raw/Version-1.0b/bingo-1.19.2-1.0.1b.jar
[1.19.2-1.0.0b]: https://github.com/J78FDK42/Bingo-1.19.2/raw/Version-1.0b/bingo-1.19.2-1.0.0b.jar
