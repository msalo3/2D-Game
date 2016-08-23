2D tile game with an overhead view

- PC can move Up, Down, Left, Right only

- each movement will activate walking animation in that direction, ending with the graphic that displays the PC looking the direction he moved

- walking animation consists of multiple graphics displayed quickly but moving along the x or y axis (depending on the movement direction)
    -Possible problem: Too hard to make walking smooth? Decrease pixels? Loop over basic walking animation for as many pixels as we need to move?

- The whole background will be a Canvas element made up of square tiles that have an order associated with them

- Each keypress (UDLR) will trigger ONE movement animation and save the PC's new position

- Obstacles will be saved in each cell as an object.

- Every movement will check if that movement is valid by looking at the cell's object

- If valid, then the movement will happen.



---KEYPRESS CODES---
  Left Arrow  - 37
  Right Arrow - 39
  Up Arrow    - 38
  Down Arrow  - 40


  W           - 119
  A           - 97
  S           - 115
  D           - 100
  Spacebar    - 32
  "Z" Key     - 90
  "X" Key     - 88
