Project Report
This project is a "Hangman" game implemented in Java. In the game, players must guess a word by selecting letters one at a time. Each incorrect guess reduces the number of available lives, and after 7 wrong attempts, the game ends. The program selects a random word from a list and displays its state with asterisks representing the hidden letters.

Design Choices and Challenges Encountered
Random Word Generation: The word for the game is randomly selected from the words array, allowing for easy expansion with additional words.
Game State Display: Initially, all letters in the word are hidden as asterisks. As letters are guessed correctly, the asterisks are replaced with the correct letter.
User Input Handling: The user is prompted to enter a single letter at a time. The program validates that the input is a letter and displays a message if an invalid character is entered.
Hangman Graphics: For each incorrect guess, a visual representation of the hangman is displayed, which builds up with each wrong attempt until the player loses all lives.
Challenges:

One challenge was ensuring proper input handling and displaying the hangman image correctly as incorrect guesses accumulated. Additionally, making sure the user could only input one letter at a time and that non-letter characters were rejected required careful validation.
Algorithms and Data Structures
Word Guessing Algorithm: For each input, the guessed letter is checked against the word. If the letter is in the word, it replaces the corresponding asterisks in the string. If the letter is incorrect, the count of wrong guesses is incremented.
Additional Notes
The program is simple to use and flexible, allowing for easy modification of the word list in the words array. You could also extend it to include additional features, such as difficulty levels or saving and loading game states.
![image](https://github.com/user-attachments/assets/16fbcc7c-1a81-43eb-8da0-47b937f10c1f)

![image](https://github.com/user-attachments/assets/8bde7998-f1fb-401a-8186-deb16f74c90b)
