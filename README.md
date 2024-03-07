Retro Run: Java Game Revival


Do you remember the good old Java games from the early 2000s? Now, let's bring back that nostalgic feeling with Retro Run! This project implements a game where you navigate a square field while being chased by artificial intelligence entities.

Game Overview


In Retro Run, the program generates a random map with obstacles, where both the player and enemies are positioned randomly. The objective is for the player to reach the target point before being caught by the enemies. Here are the game rules:

Each participant (player and enemies) takes turns making one move.
Movement directions include left, right, downward, and upward.
If an enemy is unable to move forward, it skips a turn.
The target point acts as an obstacle for enemies.
The player loses if they are caught by an enemy or unable to reach the target point.


Getting Started


To run the game, follow these steps:

Ensure you have Java installed on your system.
Navigate to the project directory.
Give execute permissions to build.sh by running sudo chmod +x ./build.sh.
Execute ./build.sh to build the project.
Run the game with specified parameters, for example:

java -jar game.jar --enemiesCount=10 --wallsCount=10 --size=30 --profile=production

Enjoy the Retro Run and relive the nostalgia of classic Java games!