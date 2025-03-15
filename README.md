# CS121_project_7

# The Java Guesser

# Algorithm 

### Display Menu

- Show the user a menu with the following options:
- 0) Exit
- 1) Human Guesser
- 2) Computer Guesser
- Prompt the user for a choice (0-2).
- Read user input.

### Handle Menu Selection

- If the user enters 0, exit the program.
- If the user enters 1, run the Human Guesser game.
- If the user enters 2, run the Computer Guesser game.
- If the input is invalid, display an error message and re-prompt.

### Human Guesser Mode

- Generate a random number between a predefined range (e.g., 1-100).
- Initialize attempt counter to 1.
- Prompt the user to enter a guess.
- Compare the guess to the random number:
- If the guess is too low, print "too low" and prompt again.
- If the guess is too high, print "too high" and prompt again.
- If the guess is correct, print "got it!" and exit the loop.
- Increment attempt counter for each guess.
- Display a congratulatory message and return to the main menu.

### Computer Guesser Mode

- Prompt the user to think of a number within a predefined range.
- Initialize variables for the guessing range (low = 1, high = 100).
- Set the initial guess as the midpoint of the range.
- Ask the user if the guess is:
- Correct → Print success message and return to the main menu.
- Too high → Adjust the high bound and guess the new midpoint.
- Too low → Adjust the low bound and guess the new midpoint.
- Repeat until the correct number is found.
- Loop Back to Menu 