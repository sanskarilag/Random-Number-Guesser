# Random Number Finding Game 🎮

A fun, interactive command-line number guessing game written in Python. You can play solo, compete with a friend locally, or challenge an AI with adjustable difficulty levels!

---

## 🚀 Features

### 1. Game Modes
*   **🤖 Play With AI**: Compete head-to-head against the computer.
*   **👤 Single Player**: Relax and try to guess the secret number in as few tries as possible.
*   **👥 Play With Friend**: Take alternating turns with a local friend to see who guesses the secret number first.

### 2. Adjustable AI Difficulties
When playing against the AI, you can select from three levels of intelligence:
*   **🟢 Easy**: The AI is clumsy, occasionally guessing completely outside the optimal range.
*   **🟡 Medium**: The AI is logical, choosing random guesses within the currently known correct bounds.
*   **🔴 Hard / Smart**: The AI uses an **optimal Binary Search** algorithm. It is highly competitive and will find the number extremely fast!

---

## 🛠️ How to Run

### Prerequisites
*   Python 3.x installed on your system.

### Running the Game
1.  Clone this repository or download the source files.
2.  Open your terminal or command prompt in the project directory.
3.  Run the game script:
    ```bash
    python random_number_finding_game.py
    ```

---

## 🎮 Gameplay & Rules

*   The system generates a random secret integer between **0 and 100** (inclusive).
*   For each guess:
    *   If the guess is correct, the player wins, and the game displays the total number of attempts.
    *   If the guess is incorrect, the system guides you by stating whether the secret number is **greater** or **smaller** than the guess.
*   In the AI and Multiplayer modes, players take **alternating turns** making guesses. The first to guess the secret number correctly wins!

---

## 📝 Technologies Used
*   **Python 3**: Core game logic.
*   **Standard Library Modules**: `random` (for number generation), `time` (for delay effects), and `math`.
