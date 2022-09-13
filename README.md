# connect-4
Connect 4 made with Java using JavaFX GUI! User interface and all logic needed for clients to play the game. Uses event driven programing. 


Each player will take a turn choosing a spot on the GridPane. After clicking a
GameButton to make a move, that button should change to the color or image that
represents that player and become disabled so it can not be pressed again.
If the “reverse move” menu item is clicked, the last GameButton clicked should become
enabled and switch back to it’s original color. It would then be that player’s, that made
that move, turn again and this should be displayed in the area that shows who’s move it
is.
In the event that there is a “connect four” either horizontally, vertically or diagonally, all
remaining enabled GameButtons should be disabled and those GameButtons that make
up the four connected spots should be highlighted. Your
game should pause for about 3-5 seconds and then switch to a third unique scene
announcing who won and allowing the users to play again or exit the program. Buttons
that restart the game or exit are fine for this scene.
