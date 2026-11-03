# Jexicon

A daily definition spelling game by smAisle. Read the definition, then spell the word one letter at a time. One wrong letter and you're out. Five themed cards a day, 25 seconds each, plus a 15-second bonus round.

- Plays at https://smaisle.app/Jexicon/
- A smAisle Daily Plus game: `?preview=1` (or the smAisle Daily app without Plus) plays today's first card as a free preview.
- `owner.html`: usage page (opens and plays per day) behind the owner's Google sign-in. Check-ins go to Firestore `jx_devices` in aislerun-88e79, from smaisle.app only.
- Single-file game: everything is in `index.html`. Bump `VERSION` on every change.

## v2.2 (Nov 2)
- Cleaner menu (change list #21): Dark mode and Sound moved to a new Settings screen.

## v2.3 (Nov 2)
- Finish screen standard: smAisle Daily button and More smAisle games row (results and the Plus gate). Usage check-in adds code, the invite code for the By code table on the stats page (change list #10). Replaces PR #3.

## v2.4 (Nov 2)
- Every card has a 25-second clock (change list #8), and running out ends the game like a wrong letter. The clock pauses while the app is away, a menu is open or the front page shows.
- Bonus round is 15 seconds (change list #9). Both clocks show an on-screen alert and play a sound at 10 and 5 seconds left.

## v2.5 (Nov 3)
- One way home (navigation standard): the yellow ‹ smAisle Daily button sits top left in the same spot on the cover and in the game, including while spelling. It replaces the footer row. smAisle Home is now a small link on the cover's version line.

## v2.6 (Nov 3)
- Correction from Jeff: the yellow ‹ smAisle Daily button shows on the cover only, never during play. During play the way back is the ‹ smAisle Daily row in the menu. The results screen keeps its row.
