# The grammar of salsa

Working notes on how salsa moves connect — and the concept behind a future app.

## The core idea
A **pattern** is a sentence. **Moves** are its words. Just as words only form a
sentence in a valid order, moves only chain if each one *starts* in the position
the previous one *left you in*.

So the structure underneath salsa is really two things:

- **Positions** — the "states." A position is the handhold plus how the partners
  face each other (open, closed, hammerlock, cross-hand, back-to-back, …).
- **Moves** — the "transitions." Every move carries you from one position to
  another across a count of music.

A move is *grammatical* at a given moment only if its starting position matches
the position you're currently in. That makes a salsa repertoire a **graph**:
positions are nodes, moves are edges, and a pattern is a path through it.

## Connectors (the grammar's punctuation)
Some moves exist mainly to *link* — they reliably return you to a neutral/home
position so something new can begin. They behave like punctuation.

- **Cuban / Casino:** *Dile que no* acts like a full stop (resets to home);
  *Enchufla* is the all-purpose joint that swaps places and opens new figures.
- **LA / On1:** the *cross-body lead* is the connective tissue — many figures are
  entered and exited through one.

Lucas dances a mix of both, so every move and pattern gets tagged with its style.

## Toward the app
If positions are nodes and moves are edges, the app can:
- **Validate** a pattern — does each move's start position match the previous end?
- **Suggest** — given where you are, which moves are legal next?
- **Generate** — find new valid paths = brand-new patterns.
- **Teach** — show the smallest graph needed for a given combination.

This file grows as the dictionary and patterns fill in and the real position
graph for Lucas's repertoire becomes visible.
