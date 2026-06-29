# ☔ Tag-ulan Trivia — Host Guide

A rainy-season **rebus** game for the PH office. 21 puzzles, 3 storm rounds, animated rain + lightning, glowing reveals, confetti.

## How to run it
1. Double-click **`index.html`** (opens in your browser — Chrome recommended).
2. Press **F** for fullscreen.
3. Plug into the projector/TV and present.

No install needed. Keep the `images/` folder next to `index.html`.
> Tip: For the fancy display font, be online when you open it (it pulls Google Fonts). Offline still works — it falls back to a bold system font.

## Controls
| Key | Action |
|-----|--------|
| **→ / Space / click** | On a puzzle: 1st press reveals the answer, 2nd press goes to next puzzle |
| **←** | Go back (hides answer if shown) |
| **R** | Toggle the answer |
| **F** | Fullscreen on/off |
| **Home** | Jump back to the title |

A presenter remote/clicker that sends arrows or clicks works out of the box.

## How to play (the round flow — 6 teams)
1. Show the rebus slide.
2. **🍾 Bottle flip** — all teams flip; the first team to land it wins the chance to answer.
3. That team gets **15 seconds** to answer (use your phone/timer — there's no on-screen timer).
4. **Miss it or time runs out?** The other teams **flip again to steal** the question.
5. Correct answer scores the point. Press → to reveal, then → again for the next rebus.

> Tip: the deck's built-in **How to Play** slide (right after the title) shows this flow — read it to the room before Round 1.

Reveal when ready. The bottom bar shows progress; top-right shows the puzzle number.

## Answer key
**☔ Round 1 — Ambon / Drizzle (easy)**
1. I UNDERSTAND — "I" under "STAND"
2. BIG DEAL — "DEAL" written big
3. SMALL TOWN — "TOWN" written tiny
4. MIND OVER MATTER — MIND over the line, MATTER under
5. SPLIT SECOND — "SECOND" split apart
6. ONCE UPON A TIME — ONCE upon TIME
7. READING BETWEEN THE LINES — READING between two lines

**🌧️ Round 2 — Ulan / Rain (medium)**
8. BACKWARD GLANCE — GLANCE reversed
9. DOWNTOWN — TOWN going down
10. TOP SECRET — SECRET at the top
11. CROSSROADS — two ROADs crossing
12. JUST BETWEEN YOU AND ME — JUST between YOU and ME
13. ONE IN A MILLION — a "1" inside MILLION
14. SIDE BY SIDE — two SIDEs side by side

**🌀 Round 3 — Bagyo / Storm (hard)**
15. UNDER THE WEATHER — THE under WEATHER
16. CALM BEFORE THE STORM — CALM (space) STORM
17. RAINING CATS AND DOGS — CAT/DOG falling like rain
18. AN EYE FOR AN EYE — EYE "4" EYE
19. ALL MIXED UP — letters of MIXED scrambled
20. SINGING IN THE RAIN — SINGING inside RAIN
21. **EVERY CLOUD HAS A SILVER LINING** — a cloud with a silver lining under it (the finale 🎉)

## Want changes?
- Edit puzzles in the `P = [...]` array inside `index.html` (each has `answer`, `how`, and the `stage` markup).
- Swap a background by replacing the matching file in `images/`.
