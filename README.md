# Tracker CE Mods

My mods for the Polyend Tracker, built on top of the
[Community Edition](https://github.com/polyend/tracker-ce) firmware. Everything the CE
does still works, I just added stuff on top.

What I added: polymeter (every track can have its own length), rotate, new chance
conditions and live fill, song repeats, per-track MIDI in, and a tempo grid in the
Sample Editor. The manual explains how each one works.

## Download

Pick the file for your device:

- Tracker Mini: [firmware/TrackerMini_CE_1.0.1.ptf](firmware/TrackerMini_CE_1.0.1.ptf)
- Tracker+: [firmware/TrackerPlus_CE_1.0.1.ptf](firmware/TrackerPlus_CE_1.0.1.ptf)
- Tracker (the original one): [firmware/PolyendTracker_CE_1.0.1.ptf](firmware/PolyendTracker_CE_1.0.1.ptf)

Manual: [Tracker-CE-Mods-Manual.pdf](Tracker-CE-Mods-Manual.pdf)

## Install

Back up the `Projects/` folder on your SD card first. Then copy the `.ptf` into the
`/Firmware/` folder, go to Config > Firmware > Firmware update, pick the file and
confirm.

## Latest fixes

- An empty MIDI track now plays the MIDI instrument of its input channel when you play
  or record on it with per-track MIDI in.
- Songs with all 255 slots filled don't break playback anymore.
- With polymeter, the end of the pattern, the next pattern in the song, the metronome
  and MIDI sync now follow the pattern length, not the length of track 1.
- Changing the MIDI in settings while holding notes no longer leaves notes hanging.

If you find a bug, open an issue here.

## License

This is a free, noncommercial community mod. It's under the same license as the
Community Edition (PolyForm Noncommercial 1.0.0 with the Polyend Additional
Permissions), see [LICENSE](LICENSE) and [NOTICE.md](NOTICE.md). It's not affiliated
with or endorsed by Polyend, so use it at your own risk.

Required Notice: Copyright (c) 2020-2026 Polyend Sp. z o.o. and Polyend Tracker Community Edition Contributors (https://github.com/polyend/tracker-ce)
