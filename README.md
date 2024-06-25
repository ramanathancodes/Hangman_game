The Hangman program randomly selects a secret word from a list of secret words. The random module will provide this ability, so line 1 in program imports it.
The Game: Here, a random word (a fruit name) is picked up from our collection and the player gets limited chances to win the game.
When a letter in that word is guessed correctly, that letter position in the word is made visible. In this way, all letters of the word are to be guessed before all the chances are over. 
For convenience, we have given length of word + 2 chances. For example, word to be guessed is mango, then user gets 5 + 2 = 7 chances, as mango is a five-letter word.


omkarpathak@omkarpathak-Inspiron-3542:~/Documents/
Python-Programs$ python P37_HangmanGame.py 
Guess the word! HINT: word is a name of a fruit
_ _ _ _ _ 

Enter a letter to guess: m
_ _ m _ _ 
Enter a letter to guess: o
_ _ m o _ 
Enter a letter to guess: l
l _ m o _ 
Enter a letter to guess: e
l e m o _ 
Enter a letter to guess: n
l e m o n 
Congratulations, You won!



You can further enhance program by adding timer after every Guess
You can also give hints from the beginning to make the task a bit easier for user
You can also decrease the chance by one only if the player’s guess is WRONG. If the guess is right, 
player’s chance is not reduced.