# LootTheRoom

Download the project files here: https://www.dropbox.com/sh/bypoqwovxiq0jjx/AAAC6iUS6JUigsSDIcXPkecpa?dl=0

An ongoing, non-commercial, self-taught project (from scratch) working with Blueprints Scripting in Unreal Engine 4.16. Please copy the entirety of the folder and make sure all the components -"Engine," "LTR2" (the folder), "LTR2" (the application), and "Manifest_NonUFSFiles_Win32"- are located in one folder together.

This project incorporates enums (for chest types and affecting the character); vectors (x/y/z world coords); looping through, modifying, and deleting arrays (they start at 0); object casting; and saving/loading data from an in-game file. The main objects are the <a href="https://github.com/sphills/LootTheRoom/wiki/RoomGeneration_BP" target="_blank">RoomGeneration blueprint</a>, <a href="https://github.com/sphills/LootTheRoom/wiki/LootChest_BP" target="_blank">LootChest blueprint</a>, and the <a href="https://github.com/sphills/LootTheRoom/wiki/ThirdPersonCharacter_BP" target="_blank">ThirdPersonCharacter blueprint</a>. Please contact me if you would like more detailed pictures of functions within each object.

To move the character, use W/S for forward/backward, A/D for left/right, and move the mouse to maneuver the camera.

Press F to open the chest you've walked up to. To open the main menu, press ESC.

This is an endless runner that consists of a room that spawns between one and three treasure chests at random within three locations in the room, each with their own type:

  1. Helpful; this chest heals you by 30 points if you're <100 (and is capped at 100), and rewards you with bonus coins if you're already full!

  2. Rewarding; this chest gives you a small amount of coins for picking it. Less than the Helpful chest, but still better than the following chest...

  3. Harmful; this chest is booby-trapped! It contains a powerful explosive and does 35 damage if you have the misfortune of opening it! If you encounter it three times in a row, that's game over man, game over.

You only get to open one chest per room, so if you're at 35 or less health and only have one chest, it might be best to move on and try again. There's no penalty for not opening a chest.

There's also a "developer's level" that shows the collision boxes to illustrate just when and how the player is detected and detects the chest. Feel free to explore that in addition to the base game.

The character model, its textures, and the textures of the walls and floor were pre-existing assets produced by the team at Epic Games.

The model of the chest and the modeled components of the room were created by me in-engine. All Blueprint scripting written by me.
