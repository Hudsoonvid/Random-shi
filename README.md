# Random-shi
Remaking whatever I think is cool with Claude

## Reaction Lyrics (`reaction-lyrics/`)

A music visualizer built on Gray-Scott reaction-diffusion. A black-and-white maze grows over the screen, every lyric word gets carved into it as an outlined letter, and then the pattern eats it back up. Open `reaction-lyrics/index.html` in a browser (it runs as a single file, no build step).

- **Song:** load an audio file (or use the mic). Beats drop blobs and push the next word. Without a song, a practice beat runs.
- **Lyrics:** type one line per phrase. Words can advance on every beat, on tap/spacebar, on a timer, or from `.lrc` timestamps (`[00:12.40] line`).
- **Randomize:** shuffles the pattern, colors, fonts, layout and tilt. Turn on Chaos to reshuffle on every new line.
- **Record:** restarts the song and saves a video (MP4 or WebM) with the audio. Pick 9:16, 1:1 or 16:9.
- Keys: `Space` play/pause (or next word in tap mode), `R` randomize, `H` hide controls.
