# HTML_Assignment
Description:
The page contains a canvas where the game is drawn.

There is a circle (target) positioned at (100, 150) with a random color.

An arrow starts from (400, 150) and moves left when the "Hit" button is pressed.

If the arrow reaches near the circle, the circle's color changes randomly.

There is also a "Reset" button, which resets the arrow's position and changes the circle's color.

Key Functionalities:
Drawing Elements:

drawCircle(): Draws a colored circle.

drawArrow(x): Draws an arrow at a given x position.

draw(): Clears the canvas and redraws the circle and arrow.

Game Mechanics:

startHit(): Moves the arrow left toward the circle and changes the circle's color if it reaches a certain point.

resetGame(): Resets the arrow's position and generates a new random color for the circle.
