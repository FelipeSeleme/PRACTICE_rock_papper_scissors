# Rock-Paper-Scissors Game

This is a simple command-line implementation of the classic Rock-Paper-Scissors game. The game is written in Python and allows a user to play against the computer. The game continues in a loop until the user decides to quit.

## How It Works

1. **User Input**: 
   - The user is prompted to input either "Rock", "Paper", or "Scissors". 
   - The input is case-insensitive, so "rock", "Rock", or "ROCK" are all valid.
   - If the user wants to quit the game, they can type "Q" or "q".

2. **Computer's Turn**:
   - The computer randomly selects one of the three options: "Rock", "Paper", or "Scissors".
   
3. **Game Logic**:
   - The game checks if the user's choice matches the computer's choice. If they match, it is a tie.
   - If the user's choice beats the computer's choice (e.g., Rock beats Scissors), the user wins.
   - If the user's choice loses to the computer's choice (e.g., Rock loses to Paper), the computer wins.

4. **Scorekeeping**:
   - The game tracks how many times the user wins, how many times the computer wins, and how many ties occur.

5. **Ending the Game**:
   - When the user types "Q" or "q", the game ends.
   - The final score is displayed, including the number of wins, losses, and ties.

## Code Structure

- **Variables**:
  - `user_wins`: Tracks the number of times the user wins.
  - `computer_wins`: Tracks the number of times the computer wins.
  - `ties`: Tracks the number of ties.
  - `options`: A list containing the choices "rock", "paper", and "scissors".

- **Main Game Loop**:
  - Continuously prompts the user for input until they choose to quit.
  - Generates a random choice for the computer.
  - Compares the user's choice to the computer's choice to determine the outcome.
  - Updates the win/loss/tie counters based on the result.

- **Game Logic**:
  - If the user's input matches the computer's choice, it's a tie.
  - If the user's input beats the computer's choice, the user wins.
  - Otherwise, the user loses, and the computer wins.

- **Final Output**:
  - When the game ends, the total number of wins, losses, and ties are printed.

## How to Run

1. **Prerequisites**:
   - Python 3.x should be installed on your system.

2. **Running the Game**:
   - Save the code in a file named `rock_paper_scissors.py`.
   - Open a terminal or command prompt.
   - Navigate to the directory where the file is saved.
   - Run the game using the following command:

     ```bash
     python rock_paper_scissors.py
     ```

3. **Playing the Game**:
   - Follow the on-screen instructions to play.
   - To quit the game, type "Q" or "q" when prompted.

