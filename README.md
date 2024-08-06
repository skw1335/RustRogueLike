Fun Roguelike ASCII Video Game coded in Rust. Followed along a tutorial designed by Herbert Wolverson. https://bfnightly.bracketproductions.com/rustbook/chapter_2.html
I followed along the tutorial to learn Rust and have a crack at coding a video game from scratch.
Turns out both of these things were very difficult.
I added a couple new ideas to new things to the Tutorial. 
In roguelikes, you find a tile that has a Downstairs type that allows us to descend to the next level, increasing the difficulty.
I decided to make the Downstairs TileType randomly assigned to the end of the map in each cardinal direction (North, South, East, West). I made sure the map wasn't blocked off by walls so the Downstairs was accessible. 
