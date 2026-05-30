# Cinema Player

A cinematic video player with an editorial film catalog aesthetic.

**Live:** [suz41.github.io/netflix-player](https://suz41.github.io/netflix-player/)

## Design

- **Typography:** Instrument Serif (display) + Outfit (body)
- **Color:** Copper-rose accent on void black, muted warm tones
- **Details:** Film grain texture, sprocket-hole progress bars, italic serif numbers
- **Vibe:** Criterion Collection archive — typographic, minimal, cinematic

## Features

- Video.js powered playback
- Episode list with progress tracking
- Subtitle sync (delay/advance per 100ms)
- Subtitle style (size, position, line gap)
- Dual audio track switching
- LocalStorage persistence (progress, settings, audio)
- Keyboard shortcuts + TV remote support

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| 0 | Subtitle delay -100ms |
| 8 | Subtitle advance +100ms |
| 1 / 3 | Line gap -/+ |
| 4 / 6 | Text size -/+ |
| 2 / 5 | Position up/down |
| G (Green) | Switch audio track |
| R (Red) | Fullscreen |
| Y (Yellow) | Restart from beginning |
| B (Blue) | Toggle subtitle bold |

## Notes

- Browsers only support MP4 and WebM containers
- MKV files need to be remuxed to MP4 first: `ffmpeg -i file.mkv -c copy file.mp4`
