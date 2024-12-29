# Python_RandomSelection
# Game Night Random Selector

## Purpose
This Python program is designed to randomly select a person from a group of players to pick the game for Game Night. It ensures a fair and fun way to decide who gets to choose.

---

## How It Works
1. **Player List**:
   - The program uses a predefined list of players (`players = ["Bill", "Roni", "Ryan", "Evan", "Clark"]`).
   - You can modify the list to include your own players.

2. **Random Selection**:
   - The program utilizes Python's `random.choice()` function to randomly select one player from the list.

3. **Output**:
   - The program prints:
     - A welcome message.
     - The name of the lucky player who gets to pick the game.
     - Specific players from the list using their index positions.

---


### Key Features:
- **Modules Used**: 
  - The `random` module is imported to enable random selection.
  
- **List of Players**: 
  - A list stores the names of participants.

- **Random Selection**:
  - The program selects a player with `random.choice(players)`.

- **Index-Based Output**:
  - The program demonstrates how to access specific elements from a list using `players[2]` and `players[4]`.

---

## Example Output

Welcome to Game Night!
Let's see who's picking tonight's game...
Tonight's lucky game picker is Ryan!
Congrats Ryan!
Ryan 
Clark


---

## How to Run
1. Install Python 3.x if not already installed.
2. Copy the code into a file named `GameNightSelector.py`.
3. Run the program: python GameNightSelector.py

   
---

## Future Improvements
- Allow user input to create a dynamic list of players.
- Add error handling for index-based prints.

---

