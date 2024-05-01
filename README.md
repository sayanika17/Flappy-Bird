# Flappy-Bird
A classic Flappy Bird game using Java's built-in graphics library, AWT/Swing. Flappy Bird is a simple game where a bird, guiding it through a series of pipes by tapping the screen to make it flap and avoid crashing.

Creating the Game Loop: The game loop is the backbone of any game. It's a continuous loop that updates the game's state, processes user input, and renders graphics to the screen. We'll implement a simple game loop using Java's Runnable interface or javax.swing.Timer.
Creating JFrame and JPanel: A JFrame is a top-level container that represents the main window of a Java application. We'll create a JFrame to hold our game. Inside the JFrame, we'll add a JPanel where we'll draw our game graphics.
Drawing Images on JPanel: Using the graphics capabilities provided by AWT/Swing, we'll draw images onto the JPanel. This includes drawing the background, the flappy bird character, and the pipes.
Randomly Generating Pipes: Pipes in Flappy Bird appear at random heights and move horizontally across the screen. We'll write code to randomly generate pipe pairs and move them from right to left.
Detecting Collisions: Collision detection is crucial for determining if the flappy bird has collided with a pipe or the ground. We'll implement collision detection logic to check if the bird has hit any pipes or gone out of bounds.
Running Score: To keep track of the player's progress, we'll add a scoring system that increments each time the player successfully passes through a pair of pipes without colliding

