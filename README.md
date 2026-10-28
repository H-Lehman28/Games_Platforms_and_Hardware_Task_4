# Games_Platforms_and_Hardware_Task_4

**Student Name:** Harry Lehman

**Student ID:** 2407002

For this task I was instructed to expans upon the 3D platfomer I created during the previous task and adjust it for the iOS ecosystem. I was taked with adding at least one more core gameplay mechanic, adding an additional level to the game and making the game transfer between them, and adding a save/load system that allows players to continue their progress after closing the game.

For the new gameplay mechanic, I added a simple score system, where the player gains points for collecting coins. To achieve this I simply added a score section to the UI and had the score text update to match the playe's score variable every time they collect a coin.  
<a href="https://ibb.co/5XnNj7WY"><img src="https://i.ibb.co/Fk0SYPbs/Screenshot-2026-10-28-221752.png" alt="Screenshot-2026-10-28-221752" border="0"></a>  

Next I created a simple second level layout and made a blueprint to transition between levels. When the player collects all 10 coins in the first level, a message appears on screen saying "Level Complete" and after 2 seconds they are transported to the second level.  
<a href="https://ibb.co/svZxftrW"><img src="https://i.ibb.co/rGV8jvJd/Screenshot-2026-10-28-222150.png" alt="Screenshot-2026-10-28-222150" border="0"></a>  
Video Demonstration: https://file.garden/al1RhDmrxi0o9o3H/Screen%20Recording%202026-10-28%20222426.mp4  

Unfortunately, despite many attempts I was unable to get a working save/load system. I had attempted a system that would save the name of the current level, and would load that level from the tile screen, but attempting to save the level name to the savegame blueprint would cause the second level to fail loading after the first level was completed.