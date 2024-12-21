Snakes and Ladders Game<br>
A C-based implementation of the classic board game Snakes and Ladders, complete with colorful visuals, animations, and an interactive gameplay experience for two players.
<br>
Features<br>
Interactive Gameplay: Two-player mode with alternating turns.<br>
Dynamic Dice Roll Animation: Simulated dice rolling with animated output.<br>
Colorful Game Board: Vibrant and visually appealing terminal-based board design.<br>
Custom Rules:
Climb ladders to advance positions.<br>
Slide down snakes when landed on.<br>
Roll a six for an extra turn.<br>
First player to reach position 100 wins!
How to Play
Run the program in a C compiler on Windows (requires conio.h and windows.h).<br>
Choose from the main menu:
Start a new game.<br>
View the game rules.<br>
Exit the game.<br>
Follow the prompts to roll the dice and move along the board.<br>
Be the first to reach position 100 to win!
Prerequisites
Operating System: Windows (uses windows.h).<br>
Compiler: A C compiler that supports libraries like conio.h and windows.h.<br>
Dependencies:
stdio.h<br>
stdlib.h<br>
time.h<br>
conio.h<br>
windows.h<br>
File Overview
SNAKEANDLADDER.c: The main source file containing the implementation of the game.
Rules
Players take turns rolling the dice.<br>
If a player lands at the bottom of a ladder, they climb to the top.<br>
Landing on a snake's head will slide the player to the tail.<br>
Rolling a six grants an extra turn.<br>
A player must roll a six to start moving from the starting position.
Contributors
T Ram Sai (124CS0037)<br>
Ayush Gatla (124CS0038)<br>
Pankaj Maulekhi (124AD0021)<br>
Abhilash Kumar (524ME0007)<br>
Screenshots
Dice Rolling Animation<br>
Colorful Game Board<br>
Winner Announcement<br>
(Consider adding images or GIFs of gameplay here.)

How to Run
Clone this repository.<br>
bash
Copy code
git clone https://github.com/<your-username>/snakes-and-ladders.git
Open the SNAKEANDLADDER.c file in your preferred C IDE.<br>
Compile and run the program.<br>
Enjoy the game!
License
This project is open-source and available under the MIT License.<br>
