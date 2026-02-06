# Multiplication Quiz (Kaboom.js)

A browser multiplication game for kids. No login, no server, no database—everything runs locally.

## How to play

- **Tables 1–10**: Answer 5 multiplication questions (e.g. 7 × 8 = ?).
- **Score**: After 5 questions you see a percentage score.
- **Unlock 11–15**: Get 100% in 5 games in a row to unlock the 11–15 multiplication tables.

Progress is saved in your browser (localStorage).

## Run locally

Open `index.html` in a modern browser (Chrome, Firefox, Safari, Edge).  
If the game doesn’t load (e.g. due to ES modules from `file://`), start a simple server from this folder:

```bash
# Python 3
python3 -m http.server 8080

# or Node (npx serve)
npx serve -p 8080
```

Then open **http://localhost:8080** in your browser.
