Twist and Spell is a fun Python-based jumbled word game built using Tkinter. Unscramble the letters to guess the correct word and boost your vocabulary skills.
## 📝 Detailed Description

**Twist and Spell** is a classic word puzzle game that challenges players to unscramble jumbled words under pressure. The game is designed with a clean and interactive GUI using Python’s Tkinter library, making it beginner-friendly yet engaging.

When the game starts, players are asked to enter their name and select a difficulty level — **Medium** or **Hard**. Based on this selection, a set of words is randomly chosen from pre-defined word lists. The letters of each word are shuffled and displayed on the screen.

Players must guess the correct word before time runs out. Each correct guess earns them points, and their score updates in real-time. If stuck, players can click the “Hint” button to reveal the first letter of the word. The game runs on a **2-minute countdown timer**, creating a fast-paced and exciting experience.

A live scoreboard displays the last 10 players' scores and durations. The game also keeps track of the **highest score**, storing the top player's name in a separate file for bragging rights!

Behind the scenes:
- The word list is read from plain `.txt` files.
- Scores and times are stored in `scores.txt` for review.
- The highest score is stored in `highscore.txt` and updates automatically.

This project is ideal for:
- Python beginners learning GUI development
- Word game enthusiasts
- Anyone looking to build a small project using files, GUI, logic, and timers
