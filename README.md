# algorithm_report
# 🧠 Memory Game (C++)

A simple memory matching game written in modern C++.  
You can choose from 3 different board sizes and test your memory by matching letter pairs. Each board is randomly shuffled to provide a new challenge every time.

---

## 📘 Introduction

This project simulates the classic [Memory Matching Game](https://en.wikipedia.org/wiki/Matching_game) in the console.  
The player must flip over two hidden tiles to find matching pairs. The game ends when all pairs have been found.

✅ Supported board sizes:
- 4x2 (Easy)
- 5x2 (Medium)
- 7x2 (Hard)

---

## 🧰 Requirements

To compile and run this project, you need:

- A C++11-compatible compiler (e.g., `g++`, `clang`, or Visual Studio)
- A terminal or console to execute the compiled binary

---

## 🛠️ How to Build and Run

### 💻 Compile

On Linux/macOS:

```bash
g++ -std=c++11 -o memory_game memory_game.cpp

g++ -std=c++11 -o memory_game memory_game.cpp


./memory_game       # On Linux or macOS
memory_game.exe     # On Windows (or double-click if compiled in IDE)


        MEMORY GAME

1. 4x2 (1)
2. 5x2 (2)
3. 7x2 (3)

Choose table size: 2

All available types are: A, E, Z, P, and D.

|   |   |   |   |   |
|   |   |   |   |   |

Type your response here (number index): 3
