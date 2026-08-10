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

**The game explains itself now** — there's a premise card before the first night and a
running objective in the corner that walks you through a complete night → day → night.
If you'd rather work it out cold, turn it off on the title screen (GUIDE: ON).

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
  12 kinds of object, seven nights.
- **Play it with sound on.** The low tone you can hear during the night is not music —
  it rises as the nearest sleeper gets closer to waking, and it's the only warning you
  get while you're looking at them instead of at the HUD. Sliders are on the title
  screen and in the pause menu.
- A run ends when the street collapses (win), when the seven nights run out, when
  your wife catches you three times, or when the neighbourhood gets suspicious enough
  to compare notes.
- Sneak. Sound carries through doorways but not through walls, and June Hoyt is a
  light sleeper.
- Every house's fridge hums at a slightly different pitch. That is on purpose.
- **There are three shops, and they stock different things.** Bulwark Mart sells you
  roughly-similar; the second-hand place sells you *nothing like it*; the antique shop
  sells you *almost exactly it*. Which one you drive to should follow from who you're
  targeting — a heavy sleeper won't register anything subtle, and someone who measures
  their shelves will spot anything that isn't near-perfect. The scanner forecasts the
  outcome before you buy, and it doesn't lie.
- Things you should tell us about: does the *doubt* band feel findable, or does it
  feel like a coin flip? Is a night long enough? Can you hear a sleeper getting close
  to waking in time to stop? Does anything read as a bug?

Single HTML file, no installer, no external requests — it runs entirely in the tab.
Desktop browser with a mouse and keyboard; it is not built for phones.

This repo holds only the built page. Source, design doc, and tooling live elsewhere.
