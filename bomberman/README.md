This is the famous Bomberman game.
   
  A map is always a square. A bomberman can navigate the map using the commands :
  forward : move forward by 1
  right : turn right without moving
  left : turn left without moving
  
  The bomberman can put bombs in the map. After being triggered, all bombs put in the map explode.
  Each bomb explosion can hit only what is directly next to it in every direction (top, bottom, left and right.
  The bomberman dies when hit by an explosion.
  
  A map can have rocks. The bomberman cannot bypass a rock. There are 3 types of rocks : 
  - a basic rock : this is the basic type. After being destroyed, it turns to a ' '.
  - a star rock : this rock hides a star that can make the bomberman move by 2 steps instead of one step. 
  				   The star can be consumed once the rock is destroyed. When a star rock is destroyed, it turns to a ''
  - an enhancer rock : this rock take a number as a parameter. This rock hides an enhancer that make the explosion's extent
  						longer according to the number passed as a parameter. 
  						It turns to the number it enhance the explosion. (example : '3' if the enhancer rock took 3 as a parameter).
  
  All rocks are represented by 'X' before being destroyed by a bomb.