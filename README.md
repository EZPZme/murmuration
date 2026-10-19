# Murmuration

*Working title.* A mancala-style game for 2 to 4 players about sowing gems around a ring of eyes to collect matching irises.

## ▶ Play it

**https://ezpzme.github.io/murmuration/**

It runs in any modern browser, on desktop or phone. You play against 1 to 3 computer opponents. No download or sign-in needed.

## How to play

**Goal:** be the first player to collect 3 irises of the same color.

**Components:** 8 eyes in a ring, 24 gems (6 each of tiger's eye, turquoise, malachite and moonstone), 36 iris cards (9 of each color) and 1 loupe.

**Setup:** place one iris face up in each eye and stack the other 28 face down as the draw pile. Put 3 random gems in each eye.

1. **Opening.** On the first player's first turn, they only place the loupe on any eye. Play then passes clockwise.
2. **Pick up.** Take all the gems from a valid eye. A **valid eye** is any eye within 2 of the loupe that has gems in it. The eye's iris stays where it is.
3. **Sow.** Drop the gems one at a time into the next eyes, clockwise. You choose which gem goes into each eye. If you have 8 or more gems, go all the way around and drop gems into the eye you emptied too.
4. **Move the loupe.** Place the loupe on the eye where your last gem landed.
5. **Win an iris.** Look at the eye where your last gem landed. If more than half of the gems there match the iris in the eye you emptied, or the iris in the eye where you landed, take that iris. You may take only one iris per turn. Exactly half does not count.
6. **Refill.** If you took an iris, draw a new iris from the pile and place it in that eye.

If the pile runs out, an eye whose iris is taken stays empty. If no irises remain on the board, the game is a draw.

## Files

- `index.html` — the complete playable game (artwork is built in; nothing else is needed).
- `art/` — the game artwork at 512 px.

## Status

Prototype for playtesting. Feedback welcome via GitHub Issues.

© 2026 EZPZme. All rights reserved. Game design and artwork may not be reused without permission.
