# 🔥 Vote-Roast — Real-Time Party Game

An interactive, chaotic, and highly engaging real-time multiplayer party game designed for 2–6 players. Perfect for group hangouts, college friends, or late-night discord calls. Roast your friends anonymously, vote on spicy questions, and guess who wrote which savage burn!

---

## 🎮 Game Flow & Rounds

### 🗳️ Round 1: Vote & Roast
* The game randomly presents a funny/provocative prompt (e.g., *"sabse jyada overacting kaun karta hai?"* 🎬).
* All players cast their vote on who fits the description best.
* The player with the most votes gets **roasted** with a dynamically generated, hilarious burn message! 🍗🔥
* Everyone receives +2 participation points to keep the spirits high.

### ✍️ Round 2: Anonymous Messages
* Every player drafts and submits a secret, funny, or savage anonymous message about other players in the room.

### 🕵️ Round 3: Guess Who Wrote It
* Match the anonymous messages displayed on the screen to the correct player who wrote them!
* Earn **+10 points** for each correct guess.
* The player with the highest total score wins the ultimate crown! 🏆

---

## ⚡ Key Features

* **Instant Lobby Access:** No annoying logins or sign-ups. Just enter a funky nickname, share the auto-generated Room Code, and play instantly.
* **Real-time Syncing:** Powered by **Firebase Realtime Database** to ensure all state transitions, votes, and messages sync instantly across all devices without page reloads.
* **Modern Material UI:** Clean dark-themed layout built with TailwindCSS, complemented by smooth card entrance animations powered by **GSAP**.
* **Smart Session Fallback:** Uses local browser storage to automatically reconnect and keep players in the lobby/game even if they accidentally reload their browser.

---

## 🛠️ Technology Stack

* **Frontend:** HTML5, TailwindCSS (styling), GSAP (animations), Font Awesome (icons).
* **Backend Database:** Firebase Realtime Database.

---

## 🚀 How to Play

1. Head over to the live deployed link (via **GitHub Pages**).
2. Enter your name and click **Create Room**.
3. Share the unique **Room Code** with your friends (minimum 2 players required, supports up to 6 players).
4. Let the roasting begin! 🌶️
