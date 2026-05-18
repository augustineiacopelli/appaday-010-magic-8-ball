# appaday-010-magic-8-ball

**AppADay · 010 · G · Games and Interactive**

Live: [augustineiacopelli.github.io/appaday-010-magic-8-ball](https://augustineiacopelli.github.io/appaday-010-magic-8-ball)

## What It Does

A fully-featured Magic 8 Ball oracle. Type a yes/no question, tap the ball (or hit Enter), and receive one of the 20 classic responses rendered inside a glowing blue triangle window — exactly as on the real toy. A history strip at the bottom tracks your last five verdicts, color-coded by outcome type.

## How to Use

1. Type your question in the input field (optional — the ball works without one).
2. Tap the ball or click **Consult the Oracle**.
3. Watch the ball shake and the answer window reveal itself.
4. Ask again as many times as fate requires.

## Technical Notes

- Vanilla HTML, CSS, and JavaScript — no dependencies, no frameworks.
- The ball is built entirely from CSS: radial gradients for the sphere sheen, clip-path polygon for the inner triangle, and layered box-shadows for depth.
- All 20 official Magic 8 Ball responses included (10 positive, 5 neutral, 5 negative).
- History chips are color-coded: blue for yes, red for no, gold for maybe.
- Fonts: Cinzel and Cinzel Decorative via Google Fonts.

## Definition of Complete

- [x] Functional: all 20 responses load, shake animation plays, answer reveals correctly
- [x] Single purpose: ask a question, get an answer
- [x] Mobile friendly: works on 375px viewport, tap targets sized correctly
- [x] Visually polished: 3D ball aesthetic with glow effects and history strip
- [x] Published: live on GitHub Pages before midnight
