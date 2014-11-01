MiniDungeon for Unity

by Steve Gargolinski
http://stevegargolinski.com
http://twitter.com/sgargolinski
steve.gargolinski@gmail.com

** THE BASICS **

This is a simple project that I wrote to help jump start anyone trying to make a random dungeon game.

Check out my blog for lots more info on the project:

http://www.stevegargolinski.com/minidungeon-a-free-random-dungeon-jump-start-for-unity/

Feel free to use this for whatever you want, just please drop me a message and let me know what you
use it for!

** CHANGELOG **

v0.2 Released 1-30-2011

- Added GoToNextFloorWhenExitIsTouched onto DungeonMetaState. When this is set to true, the player will
  automatically advance to the next dungeon floor when they touch the exit - no spacebar touch necessary.
- Added public StairsPlacementType StairsPlacement = StairsPlacementType.Random to DungeonGenerator. Also
  implements two placement types:
    - Random just chooses two random valid locations for the stairs. CreateStairsRandom()
	- AtEdges places stairs on opposite edges of the level. CreateStairsAtEdges()
- Added optional MaterialOverrideStairsUp and MaterialOverrideStairsDown variables onto DungeonGenerator,
  which will change the material on the building blocks undernearth where the stairs up and down spawn.
    - Added StairsUpBuildingBlock and StairsDownBuildingBlock materials.

v0.1 Released 1-2-2011

- Initial Release

** LICENSE **

Copyright (C) 2011 by Steve Gargolinski

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.