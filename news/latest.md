|||
09-22-2024
|||

## Walkie 1.1.0

### New Features
- Added a unique **Trinkets** slot for the Walkie, allowing players to listen to the channel they're on while not taking up an inventory slot. It will also render the player's Walkie on their back
- Added a keybind to swap the Walkie to an empty hand slot and vice versa, like the offhand swap button
- Added a scoreboard criterion for the player's last used channel
- Added a new channel, 0, that acts as a "muted" channel, making it so you can disable your walkie

### Bug Fixes
- The channel indicator no longer shows in F1
- Radio filters no longer clash with each other and cause interference
- Fixed a major memory leak

## Vendor 1.0.0
- Introduces a brand new redstone block, the Vendor.
- Includes storage for both stock and profit, each in separate menus, all in one block.
- You can configure both the product and cost item to any item. However, this binds to *item*, not *item stack*, meaning if you are selling an enchanted book, you are able to sell *any* enchanted book.
- You must have the item you want to sell and put it in the selling slot, same with cost.
- When the block is powered and a player right-clicks on the block with the cost, the trade is made with ease.
- The menu can only be opened by whoever placed the block, but the block can still be broken by anyone.
- The amount of stock that is left is displayed on an indicator on the block.
- Make the purchase by right-clicking on the Vendor with the cost item in hand.

## ComputerCraft
- Changed all textures
- Changed all recipes
- Changed various names of blocks for simplification
- Removed certain items for simplification
- Removed turtles for the sake of balancing—turtles allowed such an immense amount of automation that it would change the progression rate of the server as a whole

## General
- Added Pehkui
- Updated the main menu
- Added the "news board" to the GUI
