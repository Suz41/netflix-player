# Netflix Player

A Netflix-style video player for local and streaming video playback.

**Live:** [suz41.github.io/netflix-player](https://suz41.github.io/netflix-player/)

## Features

- Netflix-inspired dark UI
- SRT subtitle support (auto-matched by filename)
- Dual audio track switching
- Drag & drop file playback
- Playback speed control
- Keyboard shortcuts (Space, J/L, arrows, M, F)

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| Space / K | Play / Pause |
| J | Rewind 10s |
| L | Forward 10s |
| ← / → | Seek ±10s |
| ↑ / ↓ | Volume |
| M | Mute |
| F | Fullscreen |

## Notes

- Browsers only support MP4 and WebM containers
- MKV files need to be remuxed to MP4 first: `ffmpeg -i file.mkv -c copy file.mp4`
- Embedded subtitles (SRT/ASS) require external `.srt` files with matching filenames
