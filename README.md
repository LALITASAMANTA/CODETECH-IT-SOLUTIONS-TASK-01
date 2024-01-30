# CODETECH-IT-SOLUTIONS-TASK-01
Setting up Objects and Parameters:
Scanner scanner = new Scanner(System.in);: Creates a Scanner object to read input from the user.
Random random = new Random();: Creates a Random object to generate random numbers.
int minNum = 1;: Specifies the minimum number for the guessing range.
int maxNum = 100;: Specifies the maximum number for the guessing range.
int maxAttempts = 10;: Specifies the maximum number of attempts allowed per round.
int rounds = 0;: Initializes the variable to keep track of the number of rounds played.
int score = 0;: Initializes the variable to keep track of the player's score.
Displays a welcome message to the player.
The main game loop. It continues until the player decides not to play again.
Sets up a new round by generating a random target number, initializing the number of attempts, and a flag to track if the user guessed correctly.
Inner loop where the user makes guesses. Continues until the user guesses correctly or exceeds the maximum allowed attempts.
Checks if the user's guess is correct or provides feedback if it's too high or too low.
Displays a message if the user did not guess correctly within the allowed attempts.
Displays the current score and increments the rounds played.
Asksing the user if they want to play another round.
Displays the final score and a thank-you message.
Closes the Scanner to release resources.
