# **The Musical Spaceman Game**

### Intro:
This game is a fun alternative to the old hangman game. Insterad of a hangman, we are using a spaceship to blast off into space if we get the answer wrong. If you manage to get the answer correct, you will get an awesome recommendation to a song along for your troubles. 

The theme of this game is space and music. All of the phrases/words will be based around song titles.

---
### Wireframe:

![This is the basic spaceman wireframe.](/Spaceman%20Wireframe.jpg "Spaceman Wireframe")

---



**User Stories
- As a user I want to be able to Launch the Game
- As a user I want to be able to start the Game
- As a user I want to be able to guess a letter
- As a user I want to be able to know if my guess is a part of the word/phrase
- As a user I want to be able to see/keep track of my previous guesses
- As a user I want to be able to see pieces of the spaceship being built if I get an answer incorrect
- As a user I want to know if I have won
- As a user I want to know if I have lost
- As a user I want to see the leaderboard with my gaming history
- As a user I want to see a music recommendation with a link to it on Youtube

---

**MVP:**
- As a User I want to be able to <launch game>
- As a User I want to be able to <start game>
- As a User I want to be able to <make a letter guess>
- As a User I want to be able to <check if my guess is in the phrase or word>
- As a user I want to be able to <see my letter displayed on the board in its correct position(s)>
- As a user I want to be able to <see that I guessed incorrectly as a piece of the spaceship is built>
- As a User I want to be able to <see that I have won>
- As a User I want to be able to <see that I have lost> 
- As a User I want to be able to <restart/start a new game>

---

**Version 2**
- As a User I want to be able to <launch game>
- As a User I want to be able to <see the start game theme>
- As a User I want to be able to <start game>
- As a User I want to be able to <see game theme with color>
- As a User I want to be able to <make a letter guess>
- As a User I want to be able to <check if my guess is in the phrase or word>
- As a user I want to be able to <see my letter displayed on the board in its correct position(s)>
- As a user I want to be able to <see that I guessed incorrectly as a piece of the spaceship is built>
- As a User I want to be able to <see that I have won>
- As a User I want to be able to <see that I have lost> 
- As a User I want to be able to <restart/start a new game>

---
**Version 3**
- As a User I want to be able to <hear game sound>
- As a User I want to be able to <launch game>
- As a User I want to be able to <see the start game theme>
- As a User I want to be able to <start game>
- As a User I want to be able to <see game theme with color>
- As a User I want to be able to <make a letter guess>
- As a User I want to be able to <check if my guess is in the phrase or word>
- As a user I want to be able to <see my letter displayed on the board in its correct position(s)>
- As a user I want to be able to <see that I guessed incorrectly as a piece of the spaceship is built>
- As a User I want to be able to <see that I have won>
- As a User I want to be able to <see that I have lost> 
- As a User I want to be able to <restart/start a new game>


**Pseudocode:**
1. User uses the cursor to click the start game button in the game window
2. The window changes from the start window to the main window
3. The game window pops up and displays a blank word/phrase depicted by '_', a dialogue window displaying brief instructions, the title of the game, previously guessed letters
4. The User picks a letter by picking one of the letter buttons as a guess
6. The guess is checked against the hidden string to see if it is located in the string
7. If the guessed letter has been found in the string, then it is placed at its correct position
8. If the guessed letter is not found in the string, the letter is marked in the list of incorrectly guessed letters
9. After the incorrect guess, has been marked, the count for incorrect guesses is increased by 1
10. When the count increases, it triggers a change in the image of the spaceship - the more incorrect guesses, the more the spaceship is built up
11. If the incorrect guess count reaches the limit and the spaceship is fully built, the user is informed that they have lost the game
12. If the entire string is guessed without the guess count reaching its limit, then the user is informed that they have won the game
14. Once the game is over, the User is also given the option to play a new game / restart the game