# Grumbold's Trivia Tavern

A single-page trivia game where Gemma plays Grumbold, a stubborn, condescending tavern keeper who roasts wrong answers and grudgingly concedes right ones.

## Run
Open `index.html` in a browser (or `python3 -m http.server`). No build step.

- **Offline:** works out of the box with canned insults.
- **Gemma via Ollama:** `ollama pull gemma3`, run `OLLAMA_ORIGINS=* ollama serve`, then pick *Ollama* in Gemma settings.
- **Gemma via AI Studio:** pick *Google AI Studio API*, paste a key, model `gemma-3-27b-it`.

Answers are checked locally against the hardcoded questions; Gemma only writes the reaction, so judging stays fair and fast. Questions live in the `QUESTIONS` object in `index.html`.

## Demo tip
Type a contestant's name, let them answer, and watch Grumbold roast them by name.
