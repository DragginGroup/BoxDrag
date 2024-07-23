# Changelog

## UNRELEASED - 0.2.0
In the Works

## UNRELEASED - 0.1.4
- Fixed
  - Fixed F Rank Rare Tomatos
  - Fixed S Rank Animation

- Added
  - Added Custom Rank theme for F Rank
  - Added D and F rank jingle to E Rank
  - Added Custom Rank Theme for S+ Rank
  - Added Notes Hit Counter
  - Added Smooth Gameplay to Results Transition

- Changed
  - Changed Main Rank Theme
  - Changed Note Spawning Math
  - Changed Final Score with a Percentage
  - Changed Rank Nickname Display Color Changing Speed

- Engine Work
  - Added Beats and Steps
  - Added Dev and Public version Variables

- Redone
  - Rank Conditions to adapt the Percentage Scoring Type

- Behind the Scenes
  - Added New Clone Bar Type: Graph
  - Added "Development" variable for enabling certain Developer features
  - Added Turbowarp Settings
  - Fixed Clone Bar Type:  

- Work In Progress
  - Added Chart Sprite

## 0.1.3 - July 22 2024
- The RankWord Clone in the Results now Shines with the jingles like the Rank, Rank Pixel Display, and Rank Nickname Pixel Display Rank Sprite
- The Sprinkles for the "S+" Rank now go in the foreground: RankExtras Sprite
- The Speed X and Y variables are now separate from the Gravity Clone Script: RankExtras Sprite
- The Sprinkles now Go Higher when they burst out: RankExtras Sprite
- Fixed Spelling mistake on Gravity Clone Script: RankExtras Sprite
- Added Speed X Slipperyness Value to Gravity Clone Script: RankExtras Sprite
- Changed Speed X Slipperyness Value from 0.8 to 0.9 for sprinkles: RankExtras Sprite
- 200 Sprinkles now burst out instead of 100 for "S+" Rank: RankExtras 
- Added Clone Counter for Development: Affects all Sprites with Cloning
- Added Life Timer Variable to RankExtras to prevent 80+ live clones heading into gameplay also lag prevention: RankExtras Sprite
- Added DEVELOPER CLONE BAR Variable to display The Clone amount in a cool little bg graph: Backdrop, Stats, and Developer Sprites
- Fixed Bug Where Gameplay and Rank Status were in sync: Stats Sprite
- Added DEVELOPER CLONE LIMIT variable and DEVELOPER CLONE KEEPER LIST to keep track of the Clone amount for a given amount of frames: Developer Sprite
- Added 3 "Clone Bar" Modes, all enabled by the value of the DEVELOPER CLONE BAR variable: Developer Sprite
- The Mathamatics of calculating when to spawn a note now accommodates the Note Speed into the equation of random digits: EvilNote Sprite
- The Pixel Art Rank and Rank Nickname Display Now have Grids behind them: Rank Sprite
- The 8x8 Rank Display now "charges": Rank Sprite
- Removed Color effects ENTIRELY from 8x8 Rank Display: Rank Sprite
- Changed Color of 8x8 Dot "Reading' Rank Display: Rank Sprite
- Adjusted and Fixed "S+" Rank Animation: RankAnim Sprite
- Created Custom Rank Animation for "S" Rank: RankAnim, RankExtras, Stats, and Rank Sprites
- Added Rare Animation for F Rank (Animation by Djotta): RankAnim Sprite
- Adjusted F Rank Animation: RankAnim Sprite
- Properly Fixed "Good Rank" Animation: RankAnim Sprite
- Redid Rank Nicknames: Rank Sprite
- Added Asset for when the Rank Nickname Sprite is Not Available: RankAnim Sprite
- Altered Rank Sign: Rank Sprite
- Altered Positions of Rank Word, Rank Nickname Display, Rank Pixel Display, Rank, and Dev Wrench: Rank Sprite
- Altered Position of Rank Misses Counter: Stats Sprite

## 0.1.2 - July 21 2024

- Added Dev Rank Testing variable: Backdrop
- Changed Background of 8x8 Rank to an 8x8 background: Rank Sprite
- The Dots of the 8x8 Rank change to the color of the Rank slowly: Rank Sprite
- Modified the Rank Box: Rank Sprite
- Added dev wrench displayed on the Rank screen when dev Rank test is enabled: Rank Sprite
- Fixed Clipping on "E" Rank in Rank Screen: Rank Sprite
- Replaced Rank Nickname Background with Pixelart Rendition: Rank Sprite
- Offsets Based on Costume Custom Block made for Results Screen: Rank Sprite
- There is now a jingle that plays for the rank, "S+" along with the animation delay: Rank and RankAnim Sprites
- Added Sprinkles to "S+" Rank Animation: RankExtras Sprite
- Added Custom Block for creating Multiple Clones at Once: RankExtras Sprite
- Added Dev Gameplay Mode Testing Variable: Backdrop
- Added Fire Gameplay Mode (Scrapped): PlayerNote, PlayerBullet, EvilNote Sprite
- Moved Gameplay Stats to the Left: Stats Sprite
- The Score and Misses Stats on Gameplay are now Split: Stats Sprite
- Final Score counter now uses Final Score variable for colors instead of Score: Stats Sprite
- The Counting Sound Changes when it's the last number til the rank: Stats Sprite
- The Results Stats Shines when in Dev Rank Testing: Stats Sprite

## 0.1.1 - July 20 2024 

- "S+" is now a Rank: Rank Sprite
- Grey Blocks now turn into the color of the -score math variable: EvilNote Sprite
- Added Song MetaData: Song Sprite 
- Added Title Screen (not seen): Title Sprite 
- Added Level Select (not seen): LvlSel Sprite 
- Added Rank Animations: RankAnim Sprite
- Modified Rank Screen Slightly: Rank Sprite
- The Rank Music Plays after The final score is done counting: Rank Sprite
- A little jingle plays in the Rank Menu when you have a Rank that is a S or higher: Stats Sprite
- a sound plays while the final score is counting: Stats Sprite
- "C" is now the default rank: Rank Sprite
- The Final Score and Miss Counters don't change color until they are done counting (seizure prevention): Stats Sprite
- The Final Rank Color Smooths into itself starting from the initial red: Rank Sprite
- Ranks now use a custom block to determine Rank status: Rank Sprite
- Ranks are harder (or easier) to get now: Rank Sprite
- The Rank Screen now has a Rank Nickname (bad, ok, good, best, etc) Displayed on the Rank Box: Rank Sprite
- The Number Five has a Redrawn Sprite for the Rank screen: Stats Sprite
- The Rank Shines when the Rank Animation begins: Rank Sprite
- The "A" Rank has a Redrawn sprite: Rank Sprite
- There is now a jingle that plays for the ranks "F" and "D": Rank Sprites
- The Box Notes have hue shifting now: PlayerNote and EvilNote
- Removed Time Left Counter: Stats and Song Sprite
- Added outline to the Stats: Stats Sprite
- "E" is now a Rank: Rank Sprite
- Added Outlines to Rank Sprites: Rank Sprite - Changed End condition for Rank Animation: Stats Sprite
- Redid Versions (0.1.1 instead of 1.1.0 or 1.0.1)
- Added 8x8 Rank Display Art: Rank Sprite
- Added Custom Blocks for Letter/Symbols Offsets: Stats Sprite
- The letters/symbols ".", and "0" have offsets: Stats Sprite
- The Rank Word in the Rank Screen now changes color like the rank: Stats Sprite

## 0.1.0 - July 19 2024
- Initial Version
