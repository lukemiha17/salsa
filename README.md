# Salsa

A written reference of the salsa patterns I've danced, built from my own video
clips — and the groundwork for a future app about the **grammar of salsa**.

## The goal, in order
1. **Get it written down.** Every pattern from my videos, as a clean move-by-move
   sequence with names I actually understand.
2. **Understand it.** See how moves connect — entries, exits, and the moves that
   link one figure to the next.
3. **Recombine it.** Use that understanding to build new patterns deliberately.
4. **App.** A tool for the grammar of salsa — see `grammar.md`.

## How it's organized
| File / folder | What it holds |
|---|---|
| `moves.md`   | The move dictionary. Every distinct move, once. |
| `patterns/`  | One file per recorded sequence (one per video clip). |
| `grammar.md` | How moves connect, and the thinking toward the app. |
| `sources.md` | The source video clips. |
| `frames/`    | Stills pulled from the videos for analysis (disposable). |

## Status
Project structure ready. `ffmpeg` installed and the frame-reading pipeline is
tested and working. Awaiting the salsa videos from Lucas — drop them in
`videos/`, then we extract frames and write the first pattern.
