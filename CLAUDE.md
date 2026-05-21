# Salsa project — working instructions

This folder is Lucas's personal salsa-dance reference and the early groundwork
for a future app about the **grammar of salsa** — how moves connect into patterns
like words into sentences.

Owner: Lucas. Style: a mix of Cuban/Casino and LA (On1) — tag each move and
pattern with its style rather than assuming one.

## What's here
- `moves.md` — the move dictionary. Every distinct move appears once: canonical
  name, Lucas's own name for it, plain description, count/timing, lead & follow
  actions, entry position, exit position.
- `patterns/` — one file per recorded sequence; an ordered list of moves that
  reference the dictionary.
- `grammar.md` — how moves connect: positions, transitions, connectors, and notes
  toward the app.
- `sources.md` — inventory of the source video clips.
- `frames/` — stills extracted from videos for analysis. Disposable; regenerable.

## Working rules
- Source videos live in `/Users/lucasmills/Downloads/` (`IMG_2xxx.MOV`). They are
  not copied here, to save space.
- Frames are extracted with `ffmpeg`. Reading frames = reading the dance, sampled.
- **Don't invent moves, counts, or names.** Every entry must trace back to a real
  clip or to something Lucas said directly. Mark anything uncertain as uncertain.
- When the app phase starts, `moves.md` and `patterns/` should be structured
  enough to convert straight to JSON.
