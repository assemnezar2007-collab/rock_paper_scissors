# 🎮 Rock Paper Scissors Game (C++)

## 📌 Description
A simple console-based Rock, Paper, Scissors game built using C++.  
The player competes against the computer for a chosen number of rounds.

---

## 🚀 Features
- 🎯 Play multiple rounds
- 🤖 Random computer choices
- 🔄 Input validation (r / p / s)
- 🧠 Game logic to determine winner
- 📊 Score tracking for player and computer

---

## 🛠️ Technologies Used
- C++
- Standard Library:
  - <iostream>
  - <string>
  - <cstdlib>

---

## ▶️ How to Run

### 1. Compile:
g++ main.cpp -o game

### 2. Run:
./game

---

## 🧠 How It Works
1. The user chooses number of rounds.
2. For each round:
   - Player enters:
     - `r` → rock  
     - `p` → paper  
     - `s` → scissors  
   - Computer randomly selects one option.
3. The program compares choices:
   - Rock beats Scissors
   - Paper beats Rock
   - Scissors beats Paper
4. The winner is displayed and scores are updated.

---

## 🎯 Example

round - 1
choose rock or paper or scissors
r
computer choose scissors
you win
player score 1 computer score 0


---

## ⚠️ Notes
- Input must be one of: `r`, `p`, or `s`
- The game does not currently use a random seed (`srand`), so results may repeat

---

## 💡 Future Improvements
- 🎲 Add `srand(time(0))` for better randomness
- 🎨 Improve UI formatting
- 🧱 Convert to OOP (classes)
- 🏁 Show final winner after all rounds
- 🔁 Add replay option

---

## 👨‍💻 Author
- Assem albon

---

## 📜 License
This project is for learning purposes.
