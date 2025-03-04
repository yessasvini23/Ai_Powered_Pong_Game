AI Pong Game 🎮

An AI-powered Pong game built with Python and Pygame, featuring an AI vs AI mode and a Human vs AI mode. The AI uses reinforcement learning principles to improve gameplay.

Features ✨

🤖 AI vs AI mode - Two AI-controlled paddles play against each other.

👤 Human vs AI mode - Control the left paddle using arrow keys.

🎚 Multiple difficulty levels - Choose from easy, medium, or hard.

🏆 Scoring system - First to 5 points wins.

🔄 Restart option - Press R to restart after game over.

Installation 🛠

1️⃣ Clone the repository

git clone https://github.com/yourusername/ai-pong-game.git
cd ai-pong-game

2️⃣ Install dependencies

pip install pygame numpy

3️⃣ Run the game

python ai_pong_game.py

How to Play 🎮

AI vs AI Mode

The game runs automatically, with both paddles controlled by AI.

The AI adapts and improves using Q-learning principles.

Human vs AI Mode

Use UP and DOWN arrow keys to control the left paddle.

The AI will control the right paddle.

To switch between modes, change this line in the code:

human_vs_ai = True  # Set to False for AI vs AI mode

Game Rules 📜

The ball bounces off walls and paddles.

If the ball passes a paddle, the opponent scores a point.

First to 5 points wins!

Press R to restart after game over.

Contributing 🤝

Feel free to fork this repository, add new features, and submit a pull request! 🚀

License 📜

This project is open-source and available under the MIT License.

Happy coding! 🎉

