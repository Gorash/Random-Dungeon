Random-Dungeon
==============

Create a random dungeon or labyrinth in JavaScript (browser or Node JS)

demo: https://rawgit.com/Gorash/Random-Dungeon/master/demo.html

```
new RandomDungeon({
      'seed'             : 1,           // int for randomize dungeon
      'n_rows'           : 50,          // must be an odd number
      'n_cols'           : 50,          // must be an odd number
      'dungeon_layout'   : 'Normal',    // "U", "Box", "Cross" or Array of Array
      'room_min'         : 6,           // minimum room size
      'room_max'         : 10,           // maximum room size
      'room_layout'      : "Packed",         // Packed, Scattered
      'corridor_layout'  : 0,           // Labyrinth: 0, Straight: 100
      'remove_deadends'  : 0,          // percentage
      'add_stairs'       : 2,           // number of stairs
      'map_style'        : {            // "Standard", "Black" or object
          //'background'   : '#000000',
          'wall'         : null,
          'fill'         : '#000000',
          'open'         : '#FFFFFF',
          'open_grid'    : "#999999",
          'door'         : '#ff0000',
          'stair'        : '#0000ff',
        },
      'cell_size'        : 10,           // pixels
    });
```
