# 🧠 Quiz Master

A terminal-based Python quiz game with real-time stats and performance charts.

---

## Features

- **4 categories** — Science, Math, History, Technology (+ Random Mix mode)
- **Timed questions** — every answer is clocked and analyzed
- **End-game charts** — score donut, time per question, difficulty accuracy, cumulative progress
- **Session history** — tracks scores across games and plots your improvement trend
- **Difficulty levels** — Easy, Medium, Hard per question

---

## Requirements

```bash
pip install numpy matplotlib
```

## Run

```bash
python quiz_game.py
```

---

## How It Works

| Tool | Used For |
|------|----------|
| `numpy` | Avg/min/max response times, cumulative scores, accuracy by difficulty |
| `matplotlib` | 4-panel results chart + history trend graph |

---

## Project Structure

```
quiz_game.py         # Main game file (all-in-one)
quiz_history.json    # Auto-created after your first game
```

---

## Gameplay Flow

1. Pick a category and number of questions
2. Answer **A / B / C / D** — your response time is tracked
3. See your score summary with numpy stats
4. View a matplotlib chart breaking down your performance
