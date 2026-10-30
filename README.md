# Grumbold's Trivia Tavern

A single-page trivia game where a local Gemma model plays Grumbold, a stubborn, condescending tavern keeper.

Gemma does all of the work:
- **Writes the questions** for any topic the player types.
- **Judges free-text answers** (synonyms and typos are fine).
- **Roasts or grudgingly praises** the contestant by name, remembering earlier answers.
- **Delivers a final verdict** at the end of the game.

## Run
1. Start Ollama so the page may call it: `OLLAMA_ORIGINS=* ollama serve`
2. Open `index.html` in a browser (double-click it, or run `python3 -m http.server` and visit localhost:8000).
3. The game finds your installed Gemma model automatically; change it in the dropdown if needed.
4. Type a contestant name and a topic, then press **Start game**.

## Demo tip
Pick a judge or volunteer, type their name, choose a funny topic, and let them get one wrong.
