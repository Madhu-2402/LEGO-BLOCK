User Story: LEGO Block Stacking Game
Objective: As a player, I want to interact with LEGO blocks to stack them creatively, allowing for different shapes and same colors to be placed on top of each other, enabling me to build various structures.
Scenario: Initial State Setup
1.	Given the game is launched,
2.	When the game starts, all LEGO blocks are initially hidden.
3.	Then, a list Colour Box is displayed for the player to choose from.
   
Scenario: User Interaction - Placing LEGO Blocks
1.	Given the player has access to the list of Colour Box,
2.	When the player clicks on a Colour Box from the list,
3.	Then the selected LEGO block of that colour becomes visible on the floor.
4.	And the player can move these blocks onto the tiles,
5.	Then the selected LEGO block is placed on the floor.
   
Scenario: Interactions with Placed LEGO Blocks
1.	Given the player has placed at least one LEGO block of a particular colour on the floor,
2.	When the player double clicks on another Colour Box from the list,
3.	Then the clone is created on the LEGO block itself and the user has to drag it so that it becomes visible.
4.	Then the player can move these blocks onto the tiles and build them on top of each other.
   
Acceptance Criteria:
1.	Upon launching the game, all LEGO blocks are hidden initially.
2.	When the game starts, a list of Color Boxes is displayed for the player to choose from.
3.	Clicking on a Color Box from the list should make the selected LEGO block of that color visible on the floor.
4.	The player should be able to move the selected LEGO block onto the tiles.
5.	The selected LEGO block should be successfully placed on the floor upon clicking.
6.	After placing at least one LEGO block of a particular color on the floor, double-clicking on another Color Box from the list should create a clone of the selected LEGO block.
7.	The clone of the LEGO block should appear on the screen and the player should be able to drag it to make it visible.
8.	The player should be able to move these blocks onto the tiles and build them on top of each other.
9.	The stacking of LEGO blocks should be allowed, and they should align properly when placed on top of each other.
10.	 The game should prevent the placement of LEGO blocks of different colors on top of each other.
11.	 Proper error handling mechanisms should be in place to guide the player in case of any unexpected issues or errors encountered during gameplay.

