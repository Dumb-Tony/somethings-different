# Something's Different — playtest build

**Play it: https://dumb-tony.github.io/somethings-different/**

You are an alien wearing a suburban dad. You are trying to understand humans, and you
have decided the way to do that is to find out how much you can change about their
lives before they notice.

Every night you slip into a neighbour's house and swap one of their possessions for
something *almost* the same. Every morning they wake up and look at it.

- Too similar and they miss it — nothing happens.
- Too different and they're *certain* something is wrong — that's Suspicion, and
  Suspicion is how you lose.
- Land in the narrow gap between the two and they **doubt themselves**. That's the
  whole game.

## Controls

| | |
|---|---|
| W A S D | move (camera-relative) |
| Shift / Ctrl | run / sneak |
| Space | jump |
| Drag LMB / wheel | orbit camera / zoom |
| E | examine, search, open — this is the whole interaction verb |
| Tab | dossier: catalog, bag, and their state of mind |
| M | go home — ends the night and shows you the morning |
| Esc | pause |
| F3 | debug readout |

## Notes for the playtester

- It's a **vertical slice**, not a finished game: four houses, six neighbours,
  12 kinds of object, seven nights. **There is no audio yet.**
- A run ends when the street collapses (win), when the seven nights run out, when
  your wife catches you three times, or when the neighbourhood gets suspicious enough
  to compare notes.
- Sneak. Sound carries through doorways but not through walls, and June Hoyt is a
  light sleeper.
- Things you should tell us about: does the *doubt* band feel findable, or does it
  feel like a coin flip? Is a night long enough? Does anything read as a bug?

Single HTML file, no installer, no external requests — it runs entirely in the tab.
Desktop browser with a mouse and keyboard; it is not built for phones.

This repo holds only the built page. Source, design doc, and tooling live elsewhere.
