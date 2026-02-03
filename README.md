# Day 7 – Hangman 🎯

Part of my **100 Days of Python Projects** challenge.

---

## 🚀 Project Overview
The Hangman Project is a word-guessing game where the player tries to guess a randomly selected word one letter at a time.

The player starts with **6 lives**.  
Each incorrect guess reduces one life.  
The game ends when the player either guesses the word correctly 🎉 or runs out of lives 💀.

---

## 📚 What I Learned
- Using a `while` loop to control game flow
- Using a `for` loop inside a `while` loop
- Tracking and preserving previously guessed letters
- Managing game state using flags and counters
- Displaying dynamic visual feedback using stages

---

## 🛠 How It Works
- A random word is selected from a predefined word list
- A placeholder of underscores (`_`) is created based on the word length
- The player guesses letters one at a time
- Correct guesses:
  - Reveal the letter in the correct position
  - Previously guessed correct letters are preserved
- Incorrect guesses:
  - Reduce the remaining lives by one
  - Display a message informing the player
- Hangman stages are displayed after every guess
- The game ends when:
  - All letters are guessed correctly (Win)
  - Lives reach zero (Lose)

---

## 💡 Code Highlights
- Dynamic word display that updates after every guess
- Lives counter shown before each turn
- ASCII hangman stages displayed as lives decrease
- Correct handling of previously guessed letters

---

## ▶️ Example Gameplay

    | |                                            
    | |__   __ _ _ __   __ _ _ __ ___   __ _ _ __  
    | '_ \ / _` | '_ \ / _` | '_ ` _ \ / _` | '_ \ 
    | | | | (_| | | | | (_| | | | | | | (_| | | | |
    |_| |_|\__,_|_| |_|\__, |_| |_| |_|\__,_|_| |_|
                        __/ |                      
                       |___/ 

    Word to guess: _ _ _ _ _
    6/6 LIVES LEFT
    Guess a letter: a
    Word to guess: _ a _ _ _
    6/6 LIVES LEFT

    Guess a letter: z
    You've guessed z, that's not in the word. You lose a life
    5/6 LIVES LEFT

    Guess a letter: n
    Word to guess: n a _ _ _
    ...
    YOU WIN

---

## ▶️ How to Run
1. Clone the repository  
2. Run the Python file in a terminal  
3. Follow the on-screen instructions to play the game

---

## 🌐 Live Demo
https://amit7git.github.io/Python--Day-7-Hangman/
