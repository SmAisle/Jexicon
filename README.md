# Jexicon

A daily definition spelling game by smAisle. Read the definition, then spell the word one letter at a time. One wrong letter and you're out. Five themed cards a day, plus a 20-second bonus round.

- Plays at https://smaisle.app/Jexicon/
- A smAisle Daily Plus game: `?preview=1` (or the smAisle Daily app without Plus) plays today's first card as a free preview.
- `owner.html`: usage page (opens and plays per day) behind the owner's Google sign-in. Check-ins go to Firestore `jx_devices` in aislerun-88e79, from smaisle.app only.
- Single-file game: everything is in `index.html`. Bump `VERSION` on every change.
