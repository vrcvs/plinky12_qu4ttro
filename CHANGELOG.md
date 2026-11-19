# Changelog

## 1.1 – November 2026
Up to 4 of your own multisample banks at once.
- PRE opens only Plinky's system picker, which now lists your own banks in PLINKY/BANKS too and previews on the selected track itself, so auditioning never needs memory for an extra bank. The alternative SD browser (● in PRE) is gone: it was a duplicate and did not let you pick sounds on current firmware
- Song page: QU4TTRO creates its song folder on the SD card the first time the page opens; before, on a card where it had never saved, the OK pad stayed dark and nothing could be saved
- Loading a saved song now sets up the playback state (on_load_finished), as the Plinky team fixed in N3VE
- Manuals: section 9 explains your own banks in the picker, section 10 the 14 MB sample memory and the Bank Builder "Banks loaded together: 4" option (about 3 MB per bank)

## 1.0.1 – November 2026
Synced with the version in the official Plinky community-panels library (fixes by the Plinky team, thanks!).
- Fixed: loop lengths, grids, cues and other per-track settings of tracks 3 and 4 were not saved with the song
- Fixed: a sampled sound confirmed on a track could change after auditioning another sound; confirming now loads the sound into the track's own slot (sampled sounds may take a few seconds)
- Metadata header in the community-panels format
- Manuals updated

## 1.0 – November 2026
First public release.
- 4 melodic tracks on 8×6 sectors, shared key and scale, colour-coded octave/key/scale
- Live looper (first-note start, close on rec, overdub) and plonky-style step entry
- Per-track length (1–256), grid (1/2–1/32, triplets), direction, start mode, CUE, play/stop
- Pressure recording, glide on slides, mono legato
- Mixer, sound editing, system sound picker on the round pads, alternative SD browser
- Song save/load
