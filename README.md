# CYBER-SPIN

An open-source AI techno DJ by **Vinit**. CYBER-SPIN writes, beatmatches and mixes a live techno set in your browser. No server, no install, one HTML file.

## What it does

- **Writes its own tracks live, produced like real records.** A Web Audio engine with a pre-rendered drum kit (808-style metallic hats, rides, crashes, claps, snares, toms, congas), tuned layered kicks, sidechain pumping, a dark hall reverb, ping-pong delays, rolling rumble, supersaw leads, choir pads, risers, snare rolls, filter sweeps, reverse crashes and impacts. Each track runs 128 to 160 bars: intro, groove with layers entering every 8 bars, break, build and drop.
- **Genre rack with predefined beats.** Melodic techno styles in the spirit of ARGY, ANYMA, ARTBAT, CAMELPHAT and CIREZ D, each with its own drum programming, bass pattern, arps and leads. Also Warehouse, Acid, Peak time, Deep hypnotic and Melodic journey.
- **Mixes like a DJ.** Phrase-aligned 16-bar blends with a bass swap, harmonic mixing on the Camelot wheel, filtered blends when keys clash, echo-outs when tempos are too far apart.
- **Never leaves a deck empty.** When nothing is queued, it auto-sources the next track from your crate or writes an original. Swap next rerolls the pick.
- **Plays your songs exactly.** Drop MP3, WAV, FLAC, M4A, OGG or AIFF. They are queued automatically and play at their original tempo and pitch, from the first second to the last. CYBER-SPIN moves the master tempo to match your song, not the other way round.
- **Pro booth layout.** Two players with scrolling waveforms, jog wheels, Play and Cue, a two-channel mixer with EQ, color filter and echo knobs, channel faders, VU meters and a crossfader.
- **Mix by hand or let it mix.** Press Play on the waiting deck and it starts locked to the beat, then you bring it in with the crossfader and EQs. Or press Auto mix.
- **Instant genre switching.** Pick a genre card and the booth mixes into that genre within a few bars, and the whole booth takes on that genre's colour.
- **Spotify and YouTube Music links.** Those services use copy protection, so their audio can't be mixed by any outside app. Paste links or track names and CYBER-SPIN writes its own version of each, tuned to the song's mood.
- **Record the set** and save the tracklist.

## Live app

https://vinitsingh-del.github.io/cyber-spin/

## Run it

Open `index.html` in a current Chrome, Edge, Firefox or Safari. That's it.

To host it on GitHub Pages: push this folder to a repo, then turn on Pages under Settings, Pages, and pick the main branch.

To show a "View on GitHub" link in the header, set `REPO_URL` near the bottom of the script in `index.html`.

## Keyboard

`Space` drop or pause, `M` mix now, `S` skip, `N` swap next, arrow keys move the crossfader.

## Notes

- Sound starts only after you press Drop the beat. Browsers block audio until you interact with the page.
- The genre styles are original patterns inspired by each artist's signature sound. No samples, stems or melodies are copied.
- Your songs always play at their original tempo. When the next song is close in tempo (within 4%), the outgoing song is nudged during its last bars so the two blend; when it's further, CYBER-SPIN does a clean echo-out instead.
- The "Shape the set" and "Read names with Claude" features use Claude when the page runs inside claude.ai. Elsewhere they fall back to built-in logic.

## License

MIT. See `LICENSE`.
