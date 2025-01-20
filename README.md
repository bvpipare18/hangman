---

### **What is the Hangman Game?**
Hangman is a classic word-guessing game where one player (or the computer) thinks of a word, and the other player tries to guess it one letter at a time. The goal is to guess the entire word before running out of attempts (usually represented as "lives" or "guesses").

---

### **Rules of Hangman**
1. **The Word to Guess**: The game begins with a secret word, represented by underscores (`_`) for each letter (e.g., a 5-letter word would be displayed as `_ _ _ _ _`).
   
2. **Guesses**: The player guesses one letter at a time.

3. **Correct Guess**:
   - If the guessed letter is in the word, it is revealed in the correct position(s) (e.g., guessing `a` for the word `apple` would update the display to `_ _ p p _`).

4. **Incorrect Guess**:
   - If the guessed letter is not in the word, it counts as a "wrong attempt," and the player loses one guess.
   - The number of remaining guesses decreases with each incorrect guess.

5. **Winning**: The player wins if they guess all the letters of the word correctly before running out of guesses.

6. **Losing**: The player loses if they use up all their guesses (in your case, 6) without guessing the word.

---

### **How to Play Hangman with 6 Guesses**
1. **Start the Game**:
   - The game chooses a random word.
   - The word is displayed as underscores, and you start with 6 guesses.

2. **Make a Guess**:
   - Enter a letter.
   - If the letter is in the word:
     - It is revealed in all its positions.
   - If the letter is not in the word:
     - The number of remaining guesses decreases.

3. **Repeat**:
   - Continue guessing letters one by one.

4. **Game Ends**:
   - **Win**: If you reveal all the letters of the word before using up your 6 guesses.
   - **Lose**: If you run out of guesses, the word is revealed, and the game ends.

---

### **Example Walkthrough**
Suppose the secret word is **"SCALA"**.

1. **Initial Display**:
   ```
   _ _ _ _ _
   Guesses Remaining: 6
   ```

2. **Guess 1**: Player guesses `A`.
   ```
   _ _ A _ A
   Guesses Remaining: 6
   ```

3. **Guess 2**: Player guesses `S`.
   ```
   S _ A _ A
   Guesses Remaining: 6
   ```

4. **Guess 3**: Player guesses `C`.
   ```
   S C A _ A
   Guesses Remaining: 6
   ```

5. **Guess 4**: Player guesses `L`.
   ```
   S C A L A
   Guesses Remaining: 6
   ```

   The player has guessed the entire word and **wins**!

---
