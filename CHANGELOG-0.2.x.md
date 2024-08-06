# Changelog 0.2.x
## UNRELEASED 0.2.1

- Behind The Scenes
  - Added Auto-Saving for Song Data (turbowarp variations, about a minute until save)
  - Removed Loading Save Data "New status" change
  - Replaced is turbowarp use with turbowarp variable
  - Added Error Display for if a song data song is missing its song version
  - Added Loading Screens for different Menus

- Engine Work
  - Added Song Version in Song Data Instead of if it's new or not (0 or 1)

- Added
  - Added Scratch/Turbowarp hint in Credits (Misc stuff tab)
  - Added Save Icon (turbowarp variations for saving)
  - Added Song Difficulty Display
  - Added Loading Screen in Beginning
  
- Fixed
  - Fixed Some Variables were Uninitialized at the beginning
  - Fixed where if Rank Character Animation is Invalid, it goes to Box now when you would've tapped it

- Changed
  - Changed Box S Rank Conceal Beginning by 0.05 seconds. I am Serious about this change.
 
## 0.2.0 - August 4th 2024

- Added
  - ADDED 2 NEW SONGS!! Slap and Hag.
  - Added SongSelect Menu (addition/songselect-assets)
  - Added Rank Saving (resets when project resets, but in turbowarp variations you should be able to press 1 or 0 to load and save)
  - Added Credits Menu

- Engine Work
  - Added Prop List for Clones, currently stores Identifiers
  - Added easier way of adding songs

- Behind the Scenes
  - Added Sprite for Testing
  - Tested Prop Metadata [Works..?]
  - Removed LevelSel Sprite
  - Created Test Project for Testing Animation Code (addition/tests)
  - Djotta finished Credits Menu Sprite
  - Replaced Stats Menu Version Display with Title Clones
  - Added Folders
  - Added Loading Screen (not used)
  - Removed Main Menu Rank stuff
  - Added Outline to Clone Bar(s)
  - Created Test Project for Testing Asset Loading (Base/Tests/AssetLoading-Test.sb3)
  - Added "bah" Developer song for Testing stuff
  - Backdrop is now a Sprite
  - Development stuff can kinda sorta only work on Turbowarp
  - Menu Backdrop Tweens into a color now
