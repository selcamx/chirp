# Changelog

All notable changes to Chirp are documented here.

## v1.3.1 — April 2026

### New
- Auto-pause media — playing music or videos pause when recording starts, resume when done
- System Audio Recording Only — no longer requires full Screen Recording permission

### Improved
- Notch messages auto-size to fit text — no more clipped messages
- Concurrent model downloads — solo and meeting models download independently
- Cleaner download progress UI with inline layout
- Trial users now have full access to meeting mode

### Fixed
- Alignment model failed verification after download (zip extraction bug)
- Download progress UI glitched when downloading multiple model groups

### Removed
- Redundant macOS notifications for model errors and failed transcriptions

## v1.3.0 — April 2026

### New
- Speaker profiles — voices are recognized across meetings automatically
- Batch actions — re-transcribe, tag, or delete multiple recordings at once
- Speaker library — see all identified voices and single appearances

### Improved
- Better speaker detection — fewer phantom speakers from short interjections
- Handles overlapping speech — mixed-voice segments excluded from analysis
- Upgraded voice recognition model for more accurate speaker matching
- Deterministic clustering — same recording always produces the same result

## v1.2.0 — March 2026

### Improved
- Smarter speaker detection — automatically finds the right number of speakers
- Better speaker accuracy — fewer false speaker switches, especially with 3+ speakers
- No recording time limit — meetings can run as long as needed
- More reliable punctuation on all audio quality levels

## v1.1.0 — March 2026

### New
- Meeting transcription with automatic speaker labels and voice profiles
- Re-transcribe any recording — choose Parakeet (fast) or Whisper (precise)
- Run meeting diarization on any recording from the right-click menu
- Live processing indicator with current step and elapsed time
- Interrupted meetings resume automatically on next launch
- Speaker count filter in history (1, 2, 3, 4+)
- Collapsible filter sections
- Delete audio only — keep the transcription, free up space

### Improved
- History cards — cleaner layout, play button grouped with duration
- License page — side-by-side feature comparison
- Faster solo transcription — model pre-loads during recording
- Better memory management — models released when not in use
- Word highlighting stays accurate after scrubbing
- Sidebar text no longer truncates on selection

### Fixed
- Word spacing errors in solo transcription
- Numbers no longer merge with preceding words
- Context menu disabled during processing
- Re-transcription preserves original recording mode

## v1.0.0 — March 2026

### New
- 100% local transcription — your voice never leaves your Mac
- Up to 190x realtime speed powered by Apple Neural Engine
- Solo Mode — tap hotkey to dictate, text appears at your cursor
- Meeting Mode — on-device speaker identification
- Lives in your MacBook notch — always one tap away
- Searchable history with tags, filters, and audio playback
- Word-level timestamps with playback highlighting
- Export to Markdown, SRT subtitles, or plain text
- Customizable hotkeys and sound effects
