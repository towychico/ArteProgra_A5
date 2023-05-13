# ArteProgra_A5

The main functions in the code are:

1. `square(x, y)`: Draws a white square with a black outline at the given (x, y) coordinates.

2. `index(x, y)`: Converts the (x, y) coordinates of a tile to the corresponding index in the `tiles` list.

3. `xy(count)`: Converts the count of a tile to its (x, y) coordinates.

4. `tap(x, y)`: Updates the state of the game based on a click event at the given (x, y) coordinates. If the clicked tile matches the previously clicked tile, both tiles remain uncovered. Otherwise, both tiles are covered again. The game is over when all tiles are uncovered.

5. `draw()`: Draws the game board and the tiles. Also displays the number of taps and the game over message if the game is over.

The game also uses the `path()` function from the `freegames` module to load an image of a car that is displayed on the game board. The `shuffle()` function from the `random` module is used to randomize the order of the tiles.
