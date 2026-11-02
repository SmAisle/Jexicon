# Jexicon

A daily definition spelling game by smAisle. Read the definition, then spell the word one letter at a time. One wrong letter and you're out. Five themed cards a day, plus a 20-second bonus round.

- Plays at https://smaisle.app/Jexicon/
- A smAisle Daily Plus game: `?preview=1` (or the smAisle Daily app without Plus) plays today's first card as a free preview.
- `owner.html`: usage page (opens and plays per day) behind the owner's Google sign-in. Check-ins go to Firestore `jx_devices` in aislerun-88e79, from smaisle.app only.
- Single-file game: everything is in `index.html`. Bump `VERSION` on every change.

## v2.2 (Nov 2)
- Cleaner menu (change list #21): Dark mode and Sound moved to a new Settings screen.

## v2.3 (Nov 2)
- Finish screen standard: smAisle Daily button and More smAisle games row (results and the Plus gate). Usage check-in adds code, the invite code for the By code table on the stats page (change list #10). Replaces PR #3.
