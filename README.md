# QU4TTRO by VRCVS

**A four-track polyrhythmic looper panel for [Plinky 12](https://plinky12.com)** (designed for the Chords faceplate).

Four melodic tracks side by side, plonky-style: each 8×6 sector is a set of strings a fifth apart, always in key and scale, with pressure-sensitive dynamics and glide when you slide between pads. Every track has its own looper, length, grid and direction, so loops drift against each other into evolving polyrhythms.

## Features

- **4 melodic tracks**, each on an 8×6 sector of round pads, all sharing one key and scale (8 scales, colour-coded)
- **Live looping like a guitar looper**: arm, the loop starts on your first note, tap rec to close it, tap again to overdub
- **Step entry** (plonky-style): notes, chords, ties (+STEP while holding), rests (+STEP alone), legato
- **Per-track length** (1–256 steps), **grid** (1/2 to 1/32, triplets), **direction** (forward, reverse, ping-pong, random), **start point** and play/stop
- **Pressure** recorded step by step; **glide** when sliding between pads; mono legato mode
- **Mixer** (volume, pan, delay and reverb send per track), sound editing, system sound picker with instant preview
- **Song save/load**: loops, settings, the four sounds and the mix

## Install

1. Open the [Plinky 12 Code Editor](https://plinky12.com/ide.html) in Chrome.
2. Start a blank panel and paste the contents of [`src/qu4ttro.cpp`](src/qu4ttro.cpp).
3. Select **Chords** as the faceplate, press **Test** to try it in the emulator.
4. Connect your Plinky 12 via USB and press **Flash**. Panels open in other IDE tabs are flashed together.
5. Power on holding the bottom-row pad shown for QU4TTRO in the IDE diagram.

## Manual

- English: [`docs/QU4TTRO_manual_EN.pdf`](docs/QU4TTRO_manual_EN.pdf)
- Italiano: [`docs/QU4TTRO_manuale_IT.pdf`](docs/QU4TTRO_manuale_IT.pdf)

## Notes

- Very large multisample banks (around 8 MB) take a long time to load onto a track, and only one or two fit in the Plinky's sample memory at once. Lighter banks (about 1–2 MB) let you use your own sounds on all four tracks. Factory sounds load instantly.
- Tested on Plinky 12 with the Chords faceplate. Use at your own risk: custom firmware can always be restored from the Plinky 12 firmware page.

## Credits

- Freely inspired by **[plonky](https://github.com/schollz/plonky)**, the norns script by Zack Scholl (MIT), itself inspired by mmalex's original Plinky. No plonky code is used: QU4TTRO is a new implementation.
- **Plinky 12** by mmalex and Making Sound Machines.
- QU4TTRO by **VRCVS** (Filippo Rieder) – [filipporieder.com](https://filipporieder.com) · Instagram [@vrcvs](https://instagram.com/vrcvs). Written with the help of Claude (Anthropic).

## License

[MIT](LICENSE)

---

### In italiano

QU4TTRO è un pannello custom per Plinky 12: quattro tracce melodiche affiancate in stile plonky, sempre in tonalità, ciascuna con il suo looper, la sua lunghezza e la sua griglia per creare poliritmi. Installazione: incolla `src/qu4ttro.cpp` nel Code Editor di plinky12.com, prova con **Test**, poi **Flash**. Manuale completo in [`docs/QU4TTRO_manuale_IT.pdf`](docs/QU4TTRO_manuale_IT.pdf).
