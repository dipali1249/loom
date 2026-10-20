# Loom

**A brain-training game whose rules mutate.**

Loom is built on one idea: the brain grows when it has to *rebuild* its understanding, not when it repeats something it already knows. Most brain games reward fluency — you get faster at tapping shapes, and nothing else changes. Loom refuses to let you get comfortable. It teaches a small grammar of rules, then keeps rewriting that grammar, so the skill you actually practise is **adaptation**: noticing the world has changed, discarding a stale mental model, and building a new one under time pressure.

## Play

Open `index.html` in any browser. No install, no dependencies, no internet needed. It is also served via GitHub Pages.

## What this prototype contains

This is the core slice — the **mutation engine** and the **Trace**.

- **The rule mutates.** A banner tells you what to tap — TAP THE GREEN, TAP THE RED, TAP THE CIRCLES, TAP THE TRIANGLES. Every 15 seconds it changes, without warning.
- **Inhibition under load.** Colour and shape conflict on purpose (a green triangle is "go" under one rule and "no-go" under another), so no lazy habit can form. Wrong taps and missed targets both count against you.
- **The Trace.** After each 90-second cloth you see a timeline of every catch, wrong tap, miss and rule change, plus your error rate after each change versus steady play — the "adaptation dip" that the full game is designed to train.

## Design pillars

1. **The rules must move** — no mechanic is ever fully mastered.
2. **Interference over isolation** — challenges compete for the same mental resources.
3. **Show the mind, not the score** — feedback reveals how you thought, not just how well you did.
4. **Honest claims only** — no IQ promises, no fear-based notifications.

## Status

Prototype. The adaptive difficulty controller, the full four-thread system, ghost challenges and the Weave Report are not yet implemented.

## License

MIT
