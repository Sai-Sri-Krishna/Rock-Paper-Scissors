# 🪨 Rock Paper Scissors - Emoji Edition

A vibrant, interactive implementation of the classic hand game. This project demonstrates event-driven programming, score state management, and responsive CSS styling.

---

## ✨ Features
- **Visual Gameplay:** Uses high-quality emoji assets for a better user experience.
- **Dynamic Scoreboard:** Real-time updates for wins, losses, and draws without page refreshes.
- **Responsive Design:** Optimized for both mobile and desktop using Flexbox.
- **State Reset:** A dedicated reset function to clear game history and start fresh.
- **Tactile Feedback:** Hover effects and transitions to make the UI feel interactive.

---

## 🛠️ Tech Stack
- **Frontend:** HTML5, CSS3
- **Logic:** JavaScript (ES6)
- **Assets:** External emoji graphics from `supersimple.dev`

---

## 🔗 Live Demo
Test your luck against the computer here:  
[**Launch Rock Paper Scissors**](https://sai-sri-krishna.github.io/Rock-Paper-Scissors/)

---

## 🕹️ How It Works
The computer choice is determined by a pseudo-random number generator:
1. The `playGame` function generates a random index from `[0, 1, 2]`.
2. Win/Loss logic is evaluated by comparing the user input string to the computer's choice.
3. The DOM is updated dynamically using template literals to show results and the updated scoreboard.

---

## 🚀 Installation
1. Clone the repo:
   ```bash
   git clone [https://github.com/Sai-Sri-Krishna/Rock-Paper-Scissors.git](https://github.com/Sai-Sri-Krishna/Rock-Paper-Scissors.git)
