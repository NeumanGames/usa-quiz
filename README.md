# 🗺️ USA Explorer — States & Capitals Quiz

*A free learning game by NeumanGames™*

An interactive geography quiz that helps 4th grade students learn all 50 US states and their capitals through maps, shapes, and smart practice.

---

## What It Is

USA Explorer is a single HTML file that runs in any web browser — no app store, no installation, no internet required after the first load. Students study the **geographic shape and location** of every state, and learn all 50 **capital cities**, through four different quiz modes and a built-in learning algorithm that focuses practice where it's needed most.

---

## How to Use It

### Opening the App

Open the file in any web browser or visit the hosted URL. Works on any device with a web browser. On a tablet or mobile device, use your browser's **"Add to Home Screen"** option to save it as a full-screen app icon for easy access.

---

### Choosing a Quiz Mode

Four modes are available at the top of the screen:

| Mode | How It Works |
|---|---|
| 🔵 **Name That State** | A state lights up yellow on the map — pick its name from 4 choices |
| 📍 **Click The State** | A state name appears — tap the correct shape on the map |
| 🏛️ **Name The Capital** | A state highlights on the map — pick the correct capital city from 4 choices |
| 🗳️ **Capital → Click State** | A capital city name appears — tap the correct state on the map |

Switch modes any time. Your progress carries over across all modes.

---

### Display Options

Two toggles in the top-right corner of the header:

- **Show abbreviations** — displays the two-letter state code (AL, CA, TX…) inside each state shape. Turn this off for a harder challenge once the locations are familiar.
- **Show state names on hover** — moving the mouse or stylus over any state shows its full name in a tooltip. Useful when studying capitals, but best turned **off** when quizzing on state names so it does not give away the answer.

---

### Score Bar

The three pills below the mode buttons track the current session:

- 🟢 **Correct** — total right answers this session
- 🔴 **Wrong** — total wrong answers this session
- 🔥 **Streak** — consecutive correct answers (hitting 3 in a row triggers a confetti celebration)

---

### Progress Panel

Click **"📊 Progress — Show"** to expand the progress tracker. It displays all 50 states as small colored tiles:

| Color | Meaning |
|---|---|
| ⬜ Gray | Not yet seen |
| 🟡 Yellow | Seen but still learning — answered incorrectly or no streak yet |
| 🔵 Blue | Familiar — at least one correct answer in a row and over 50% accuracy |
| 🟢 Green | Mastered — three or more correct in a row and over 75% accuracy |

Hover over any tile to see exact stats for that state (how many times seen, accuracy percentage). The goal is to turn all 50 tiles green.

---

### How the Learning Algorithm Works

The app uses a **spaced repetition** system — the same technique used in professional flashcard apps — adapted for 4th grade geography:

- **States never seen** are introduced with high priority so all 50 are encountered over time
- **Wrong answers** bring that state back quickly and more often until the student gets it right
- **Correct answers** gradually reduce how often that state appears — one right answer lowers the frequency, two in a row lowers it further, and three or more in a row moves the state to rare review
- **Distractors** (the wrong choices in multiple choice) are drawn from the states the student is currently struggling with most, making the wrong options meaningfully challenging rather than random
- A **cooldown** of 4 questions prevents the same state from appearing back-to-back, so repetition feels natural rather than mechanical

The result is that a student who keeps getting Texas right will see it less and less, while a state like Rhode Island that keeps getting confused will reappear frequently until it sticks.

---

## Tips for Teachers and Parents

- Start with **"Show abbreviations" on** and **"Show state names on hover" on** while the student is still learning locations
- Once locations are familiar, turn **abbreviations off** so students recognize shapes without the label hint
- Turn **hover tooltips off** when quizzing on state names — otherwise the tooltip gives the answer away
- The **Click The State** and **Capital → Click State** modes are harder than multiple choice and good for students who are ready for a real challenge
- Progress is saved within a single browser session. Refreshing the page resets progress, so encourage students to complete a full practice session before closing

---

## Files

| File | Description |
|---|---|
| `index.html` | The entire NeumanGames™ USA Explorer app — rename `us_states_quiz.html` to `index.html` for GitHub Pages |
| `README.md` | This document |

To use on GitHub Pages, rename the quiz file to `index.html`, push both files to a public repository, and enable GitHub Pages in the repository Settings under Pages → Source → main branch.

---

## Support NeumanGames™

Every game on this platform is free, forever. If USA Explorer has been helpful for a student in your life, your support helps us build the next one.

- 🎁 **One-time donation:** [ko-fi.com/neumangames](https://ko-fi.com/neumangames)
- ⭐ **Monthly support & community:** [patreon.com/NeumanGames](https://www.patreon.com/NeumanGames)

Works on any device with a web browser — no login, no download, no cost.

---

## Legal

NeumanGames™ is a trademark of NeumanGames. All rights reserved.

This game is provided free of charge for educational use. No reproduction or redistribution for commercial purposes without permission.

© NeumanGames™ — [neumangames.github.io](https://neumangames.github.io)
