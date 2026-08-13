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

**If it's too hard, change it.** There's a difficulty button on the title screen —
GENTLE / STANDARD / HARSH. It moves the win bar and how fast the street reacts, together.
The day screen shows how close you are, so you can see it working.

**The game explains itself now** — there's a premise card before the first night and a
running objective in the corner that walks you through a complete night → day → night.
If you'd rather work it out cold, turn it off on the title screen (GUIDE: ON).

## Controls

| | |
|---|---|
| W A S D | move (camera-relative) |
| Shift / Ctrl | run / sneak |
| Space | jump |
| Mouse | look around — **click once to capture the cursor**, Esc releases it |
| Wheel | zoom |
| E | examine, search, open — this is the whole interaction verb |
| Tab | dossier: catalog, bag, and their state of mind |
| M | go home — ends the night and shows you the morning |
| Esc | pause |
| F3 | debug readout |

## Notes for the playtester

- It's a **vertical slice**, not a finished game: four houses, six neighbours,
  30 kinds of object, ten nights.
- **Play it with sound on.** The low tone you can hear during the night is not music —
  it rises as the nearest sleeper gets closer to waking, and it's the only warning you
  get while you're looking at them instead of at the HUD. Sliders are on the title
  screen and in the pause menu.
- A run ends when the street collapses (win), when the ten nights run out, when your
  wife catches you three times, or when the neighbourhood gets suspicious enough to
  compare notes.
- **Spread your work across the whole street.** The win condition is a *mean* over the
  six neighbours, so ruining two people and ignoring four cannot get you there no
  matter how thorough you are. Roughly four objects a night, across different houses,
  is a winning pace.
- Sneak. Sound carries through doorways but not through walls, and June Hoyt is a
  light sleeper.
- Every house's fridge hums at a slightly different pitch. That is on purpose.
- **The street fights back.** As the neighbourhood gets rattled it starts installing
  things and they never come off: motion lights over the porches, dogs left out in the
  yards, a man walking the street at 2am, doorbell cameras, and eventually somebody in
  each house awake all night. Succeeding is what triggers it, so a good run gets
  harder rather than easier. The morning report tells you each time it happens.
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




