# Vite Memory Game 🎴

A simple memory (“match the pairs”) game built using **React** + **Vite**.  
Flip cards, match pairs, and try to finish in as few moves as possible!

---

## 🚀 Live Demo

*(If deployed, put your hosted link here — e.g. via Vercel or Netlify)*  
[View Live Game](https://your-deployment-link.com)

---

## 📁 Project Structure

```
vite-memory/
├─ public/
│   └─ img/             # your card images (helmet-1.png, sword-1.png, etc.)
├─ src/
│   ├─ App.jsx          # main component & logic
│   ├─ index.jsx        # app entry point
│   └─ App.css           # styles
├─ .gitignore
├─ index.html
├─ package.json
└─ vite.config.js
```

---

## 🛠 Features & Functionality

- Shuffle deck of cards (duplicate & randomize)  
- Flip two cards and check for match  
- Track number of turns / moves  
- “New Game” button to reset and reshuffle  

---

## 🧩 How to Run Locally

1. Clone this repo  
   ```bash
   git clone https://github.com/amanselman/vite-memory.git
   cd vite-memory
   ```

2. Install dependencies  
   ```bash
   npm install
   ```

3. Start dev server  
   ```bash
   npm run dev
   ```

4. Open the URL shown (usually `http://localhost:5173`) in browser  

---

## ✅ How to Play

1. Click **New Game** to shuffle and lay down the cards  
2. Click a card to flip it, then click another  
3. If they match, they stay face up; otherwise, they flip back  
4. Your goal: match all pairs in the least number of turns  

---

## 🧰 Tech Stack

- **React** — UI  
- **Vite** — build tool & dev server  
- **JavaScript / JSX**  
- **CSS** — styling  

---

## 📝 To-Do / Future Improvements

- Add animations / flip transitions  
- Add a timer or score leaderboard  
- Mobile / responsive design  
- Add sounds on match / mismatch  
- Use TypeScript & stricter typing  
- Add levels, larger decks  

---

## 🎉 Credits & License

- Card images from your `public/img` directory  
- You (author) — feel free to add your name / contact  
- Licensed under **MIT License** — see `LICENSE` for details  
