# 3-Missionaries-and-3-Cannibals-Game
The Goal 🎯
The objective is to safely transport all three missionaries and three cannibals from the right bank of a river to the left bank using a single boat.

How it Works
The script keeps track of the number of missionaries and cannibals on each side of the river and the position of the boat. It uses a while loop to continuously ask for your next move.

Visual State: The game's current state is displayed using emojis, showing who is on which bank and where the boat is.

Missionary: 💂

Cannibal: 👹

Boat: 🛶

River: 🌊

User Input: You are prompted to enter the number of missionaries and cannibals you want to put on the boat for the next trip.

State Update: The script updates the counts of people on both banks based on your input and moves the boat to the opposite side.

Win/Lose Conditions: After every move, the script checks for two conditions:

You Lose ☠️: If on either bank, the number of cannibals outnumbers the number of missionaries (and there's at least one missionary present).

You Win 🎉: If you successfully move all six people to the left bank.

Game Rules Enforced by the Code:
The code ensures you follow the puzzle's rules by validating your moves:

The boat can only carry a maximum of two people.

The boat cannot be empty when it crosses the river.

You cannot move more missionaries or cannibals than are currently on the bank where the boat is located.
