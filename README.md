# Study Quest

Retro arcade study game with two courses:

- **American Civics** – U.S. naturalization civics questions (7 levels)
- **CNA Exam Prep** – 300 nursing assistant written-exam practice questions (20 levels, grouped by exam category)

Each course has an **Arcade** mode (timer, lives, combos, high scores) and a **Study** mode (no timer, no lives, missed questions come back until answered correctly). Progress is saved in the browser.

## Files

- `index.html` – the whole game (course select, levels, quiz engine)
- `data/civics.js`, `data/cna.js` – question data

## Run / deploy

Open `index.html` in a browser. It is a static site with no build step, so on Vercel import the repo with the "Other" framework preset and leave the build command empty.
