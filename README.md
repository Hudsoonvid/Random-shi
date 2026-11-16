# Random-shi
Remaking whatever I think is cool with Claude

## Reaction Lyrics (`reaction-lyrics/`)

A music visualizer built on Gray-Scott reaction-diffusion. A black-and-white maze grows over the screen, every lyric word gets carved into it as an outlined letter, and then the pattern eats it back up. Open `reaction-lyrics/index.html` in a browser (it runs as a single file, no build step).

- **Song:** load an audio file (or use the mic). Beats drop blobs and push the next word. Without a song, a practice beat runs.
- **Lyrics:** type one line per phrase. Words can advance on every beat, on tap/spacebar, on a timer, or from `.lrc` timestamps (`[00:12.40] line`).
- **Randomize:** shuffles the pattern, colors, fonts, layout and tilt. Turn on Chaos to reshuffle on every new line.
- **Record:** restarts the song and saves a video (MP4 or WebM) with the audio. Pick 9:16, 1:1 or 16:9.
- Keys: `Space` play/pause (or next word in tap mode), `R` randomize, `H` hide controls.

## Grain Drain (`grain-drain/`)

An original falling-sand puzzle. A picture made of colored sand sits over a 6×6 board of trays. Drag (or tap) a tray into the top row and any sand of the same color at the bottom of the picture pours into it. Full trays pop and free up room, and you clear the picture by draining every grain. Six hand-drawn pictures, then it loops with new boards. Open `grain-drain/index.html` in a browser.

## Choir of One (`choir-of-one/`)

Turns sheet music into a song made only of your voice. Load a score, sing each instrument's part one at a time, and all the takes get layered in time into the whole song. Open `choir-of-one/index.html` in a browser (it needs the microphone, so use Chrome, or serve it over https/localhost). Wear headphones.

- **Song:** open a MusicXML file (`.musicxml`, `.xml`, `.mxl`) or a MIDI file (`.mid`), or type notes like `C4 D4 E4:2 R:1` with `---` between instruments. Most notation apps and MuseScore can export these. Photos and PDFs of sheet music are not read.
- **Sing each instrument:** every part gets a row. Record gives a four-beat count-in, then shows the note to sing right now, the next one, and a live in-tune meter while a line moves across the score. The guide can play a click, the part's own notes and the other parts. Octave moves a part into your range.
- **Collage:** a piano roll of the whole song, filled in part by part as you record. Play it, or save it as a WAV. A synth covers parts you haven't sung yet, each part has a volume, and "Voice timing" lines your takes up with the beat.
