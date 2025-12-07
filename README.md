# 🕵️ F‑*‑F‑O  
**F*ck Around and Find Out — an immersive word deduction arcade game**

---

## 📖 Overview
FAFO is a cinematic word deduction game where players guess a hidden word in six tries.  
Each guess provides feedback on letter accuracy, and players earn points to spend on clues.  
The design emphasizes accessibility, modularity, and arcade polish.

---

## 🎯 Objectives
- Challenge players to deduce the hidden word efficiently.  
- Provide a scoring and clue system to balance risk and reward.  
- Deliver an immersive arcade‑style experience with sound, animation, and responsive UI.  
- Track player progress with stats and history for replayability.  

---

## 🕹️ Gameplay
1. Fill the grid with letters using the keyboard or on‑screen keys.  
2. Press **Enter** to submit a guess.  
3. Feedback is given for each letter:  
   - 🟩 Correct letter, correct position  
   - 🟨 Correct letter, wrong position  
   - ⬜️ Letter not in word  
4. Earn points for correct guesses.  
5. Spend points to buy clues (random letter, first letter, last letter).  
6. Win by solving the word within six tries.  

---

## ✨ Features
- **Daily Mode** — one puzzle per day.  
- **Random Mode** — unlimited puzzles for practice.  
- **Clue Purchase System** — spend points to reveal letters.  
- **Stats & History** — track games played, win rate, streaks, and guess distribution.  
- **Arcade Audio** — background music and sound effects.  
- **Accessibility** — keyboard input, focus management, responsive layout.  

---

## 🛠️ Technologies
- **HTML5 / CSS3** — semantic structure and retro arcade styling.  
- **JavaScript (ES6)** — game logic, scoring, and clue system.  
- **LocalStorage** — persistent stats and streaks.  
- **Audio** — immersive background music and sound effects.  

---

## 📂 Project Structure

-fafo/ ├── index.html     # Main game UI ├── assets/ │   ├── style.css     # Styling │   ├── sounds/       # Arcade sound effects │   └── images/       # Optional assets ├── script.js         # Game logic └── data/ └── wordBank.js   # Word list

---

## ♿ Accessibility
- Keyboard input supported for all gameplay.  
- Focus management ensures Enter key doesn’t “stick” to clue buttons.  
- Containers (`#game-grid`, `#keyboard`) are focusable for smooth navigation.  
- ARIA roles and labels used for modals, navigation, and live regions.  

---

## 🔮 Future Improvements
- Add multiplayer or competitive modes.  
- Expand word bank with difficulty levels.  
- Enhance animations and sound effects for more arcade polish.  
- Implement leaderboards and social sharing.  

---

## Sounds

Sound Effect by <a href="https://pixabay.com/users/freesound_community-46691455/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=54828">freesound_community</a> from <a href="https://pixabay.com/sound-effects//?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=54828">Pixabay</a>

---

## 👨‍💻 Credits


Built by Pierre with a focus on modularity, accessibility, and arcade polish.

---

## 📜 License
This project is licensed under the MIT License — feel free to use, modify, and share.


