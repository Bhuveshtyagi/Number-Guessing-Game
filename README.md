# Number-Guessing-Game
Build a simple number guessing game to test your luck.
A simple and interactive command-line Number Guessing Game written in Python. The computer randomly selects a number between 1 and 100, and the player tries to guess it within a limited number of chances based on the chosen difficulty level.

---

## 🎮 Features

- **Random Number Generation**: Generates a random secret number between 1 and 100.
- **Multiple Difficulty Levels**:
  - **Easy**: 10 chances
  - **Medium**: 5 chances
  - **Hard**: 3 chances
- **Real-time Feedback**: Provides hints whether your guess is `"too high"` or `"too low"`.
- **Remaining Chances Tracker**: Displays remaining chances after each guess.
- **Score & Attempt Counter**: Shows the total number of attempts taken to guess correctly upon winning.
- **Zero External Dependencies**: Built strictly using Python's built-in `random` module.

---

## 📋 Prerequisites

- **Python 3.x** installed on your system.

Check your Python version by running:
```bash
python3 --version
```

---

## 🚀 How to Run

1. Clone or download the project files into your desired directory.
2. Open your terminal or command prompt and navigate to the project folder:
   ```bash
   cd /path/to/project
   ```
3. Run the script:
   ```bash
   python3 merge_audio_video.py
   ```

---

## 🕹️ Gameplay Example

```text
Welcome to the Number Guessing Game!
I'm thinking of a number between 1 and 100.
You have 5 chances to guess the correct number.
Please select the difficulty level:
1. Easy (10 chances)
2. Medium (5 chances)
3. Hard (3 chances)
Enter your choice: 1

Great! You have selected the Easy difficulty level.
Let's start the game!
enter a number b/w 1-100: 50
too high
Chances left: 9
enter a number b/w 1-100: 25
too low
Chances left: 8
enter a number b/w 1-100: 37
too low
Chances left: 7
enter a number b/w 1-100: 43
Congratulations! You guessed the correct number in 4 attempts.
```

---

## 📁 Project Structure

```text
├── project.py   # Main Python game script
└── README.md              # Project documentation
```

---

## 🔗 Project URL
https://roadmap.sh/projects/number-guessing-game

## 🛠️ Future Improvements

- Input validation for non-numeric user inputs.
- Option to play again without restarting the script.
- High score / best attempts tracking across sessions.
- Timer to track the time taken to guess the number.
