# 🧠 Ethan's Brain Gym

A personalized adaptive math problem app for cognitive rehabilitation — built for Ethan.

## Features

- **200+ curated problems** across all difficulty levels (arithmetic, algebra, geometry, calculus, logic, riddles, word problems)
- **Infinite generated problems** — arithmetic, algebra, and geometry problems are generated on the fly for unlimited variety
- **Adaptive difficulty** — difficulty automatically adjusts based on performance (5/5 → harder, ≤2/5 → easier)
- **Geometry visuals** — shapes rendered in JavaScript Canvas (rectangles, circles, triangles, cylinders, etc.)
- **Session stats** — tracks correct answers, accuracy, average difficulty, streaks, and per-difficulty breakdown
- **Progress history** — download session JSON files and load them back to see progress over time

## Problem Types

| Type | Difficulty | Examples |
|------|------------|---------|
| Arithmetic | 1–3 | Addition, multiplication, powers, percentages |
| Fractions | 2–3 | Add/subtract/multiply fractions |
| Algebra | 2–5 | Linear equations, quadratics, functions, logarithms |
| Geometry | 2–4 | Area, perimeter, Pythagorean theorem, volumes |
| Word Problems | 2–4 | Speed/distance, ratios, interest, mixtures |
| Statistics | 3–4 | Mean, median, mode, range, standard deviation |
| Probability | 3–5 | Basic probability, combinatorics |
| Trigonometry | 4 | SOH-CAH-TOA, unit circle, identities |
| Calculus | 5 | Derivatives, integrals, limits, FTC |
| Number Theory | 4–5 | GCD/LCM, primes, divisibility |
| Logic | 3–5 | Syllogisms, quantifiers, conditionals |
| Riddles | 1–3 | Fun brain teasers for variety |

## Difficulty Scale

| Level | Label | Description |
|-------|-------|-------------|
| 1 | Very Easy | Single-digit arithmetic, simple counting |
| 2 | Easy | Multi-digit math, basic fractions, simple geometry |
| 3 | Medium | Algebra, circle geometry, percentages, word problems |
| 4 | Hard | Quadratics, systems, trig, probability |
| 5 | Challenge | Calculus, number theory, proofs, complex algebra |

## How It Works

1. Click a difficulty level or press **Start** to begin
2. 5 problems appear per batch with multiple-choice answers
3. After each batch, difficulty adjusts automatically
4. Explanations appear after each answer
5. Use **Download Session Data** to save progress as JSON
6. Load past session files via **History** to see progress charts over time

## Setup (GitHub Pages)

1. Create a new GitHub repository (e.g., `ethan-brain-gym`)
2. Upload both files:
   - `index.html`
   - `problems.json`
3. Go to **Settings → Pages** in your repository
4. Under **Source**, select `Deploy from a branch`
5. Choose `main` branch and `/ (root)` folder
6. Click **Save**
7. Your site will be live at `https://YOUR_USERNAME.github.io/REPO_NAME/`

## Tracking Progress Over Time

Session data is automatically saved in the browser's localStorage (survives page refreshes).  
To track progress across multiple days:
1. At end of each session, click **Download Session Data**
2. Save the file (named by date automatically)
3. On future sessions, open **History** and load past session files to see the progress chart

## Tips for Ethan

- Start on **Easy** mode and let the system bring you up naturally
- No pressure — the difficulty will always come back down if needed
- The riddles and word problems are meant to be fun breaks!
- Short sessions are great — even 1 batch (5 problems) counts
