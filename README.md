# Break Breaker 💥🔨

Break Breaker is a simple Java game where the player controls a paddle to bounce a ball and break all the bricks on the screen.

# 🚀 Getting Started

To get started, clone the repository and run the Main.java file.
$ git clone https://github.com/Theyashsawarkar/Break-Breaker.git
$ cd Break-Breaker
$ javac Main.java
$ java Main

# 🎮 How to Play

Use the left and right arrow keys to move the paddle. Bounce the ball off the paddle and break all the bricks on the screen to advance to the next level. If the ball falls below the paddle, you lose a life. You have three lives per game.

# 💻 Technical Details

- The game is built using Java Swing, a graphical user interface (GUI) toolkit for Java. Swing provides a rich set of customizable components for building desktop applications with a consistent look and feel. In Break Breaker, Swing is used for both the game graphics and user interface.

- The Main.java file initializes the game window and sets up the game loop. The Gameplay.java file handles the game mechanics, including ball movement, collision detection, and scoring. The MapGenerator.java file generates the bricks for each level based on a 2D array of integers representing the brick layout.

- The game is structured using the Model-View-Controller (MVC) design pattern. The model contains the game data and logic, the view is responsible for rendering the game graphics, and the controller handles user input and updates the model and view accordingly.

- The game loop runs at a fixed frame rate of 60 frames per second (FPS) using the java.util.Timer class. The timer triggers the actionPerformed() method in Gameplay.java, which updates the game state and repaints the screen.

Overall, Break Breaker is a simple yet fun example of a Java game using Swing and the MVC design pattern.

# 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

# 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.
