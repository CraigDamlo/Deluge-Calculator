# Deluge Calculator

A mobile-friendly web calculator for the [Synthstrom Deluge](https://synthstrom.com/). Calculate song length from BPM, time signature, sections, and bars per section.

Themed with [Dracula Classic](https://draculatheme.com/).

## Usage

Enter your song structure and the total duration calculates instantly:

- **BPM** — your song's tempo (default: 120)
- **Time Signature** — numerator / denominator (default: 4/4)
- **Bars per Page** — how many bars fit in one page (16 steps) at your current zoom level. 4 for quarter-note resolution in 4/4, 1 at default 16th-note zoom.
- **Total Pages** — the length of your song, in pages

Bar length, page length, total bars, and beats per bar display alongside the song length.

## Notes

- Beats per bar scales the time-signature numerator against a quarter-note denominator, so duration stays accurate for compound meters (e.g. 6/8, 3/4)
- Works offline once loaded — bookmark it on your phone

## Live Version

https://craigdamlo.github.io/Deluge-Calculator

## License

MIT
