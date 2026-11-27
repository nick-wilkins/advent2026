# Digital layer

Technology brings the Professor and the world to life with minimal screen time. Build only after the storyline and Stage 3 communication requirements are fixed. Do not overengineer.

## Audio

- Prerecorded only (no live conversational AI), for full control of continuity and content.
- ElevenLabs: one consistent original voice for the Professor; a second for Rowan (see `04-characters.md`).
- 8 to 10 significant transmissions across the month; most days have none. Calls of 20 to 90 seconds.
- Forms: incoming calls, voicemails, expedition updates, interrupted messages, congratulations, gentle warnings, final briefing.
- Atmosphere: phone distortion, radio interference, rain, jungle, laboratory, distant trains, rustling maps, a disconnect click.
- Some transmissions at dinner time rather than breakfast.

## AI imagery

- Consistent visual identity for the Professor (and a young Thistlewick and Rowan for the 1976 and 1984 photos).
- Use photos of the real props as references: the Professor with the actual mortar, examining the actual chess pieces, the Stone on his desk, the Engine's original design, a figure in the background, deliberate hidden clues.
- Printed as physical photographs, labelled and placed in envelopes or evidence bags. Children should recognise the objects when they find them.

## Communications terminal (this Laravel app)

A communication device, not a game.

- Child device: incoming-call screen with accept/decline, Professor portrait, audio playback (starts on Accept to satisfy autoplay rules), simple terminal with occasional password entry, incoming evidence photograph, emergency transmissions.
- Parent panel: pick a prerecorded transmission, trigger a call on the other device, play sound effects, unlock a message, show a photograph, trigger the final call.
- Transport: Reverb/WebSockets or simple polling, whichever is simplest.
- **Not wanted:** dashboards, scores, digital inventories, achievements, games.
