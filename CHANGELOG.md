# Changelog

All notable changes to Chirp are documented here.

## v1.4.6 — May 2026

### New
- Ping — a built-in feedback form right in the sidebar. Bugs and features become public GitHub issues; support and other go to private email.
- Welcome panel after every update — the first launch of a new version auto-opens with the release notes.
- Auto-update checks now run four times a day. The version chip subline shows when the last check happened — "Checked 2h ago".

### Improved
- About popover redesigned — version info now lives in its own header bar above the brand zone, so the logo and tagline read as identity again.
- Update flow is smoother across the board: confirmation messages stay long enough to read, the action button now says "Install" instead of "Restart", and cancelling mid-update no longer leaves things half-done.
- Calmer update chip — checks pulse with a quiet ellipsis instead of a loading wheel, and the success checkmark springs in with confidence.
- Update progress now sweeps continuously across download + prepare — no more reset at the handoff between phases.
- Diagnostic reports now include speed measurements, hotkey assignments, and behavior settings — fewer round-trips when something needs support.
- Menu bar dropdown — Check for Updates and Send Feedback both work directly from the menu now, no need to open Settings first.

### Fixed
- "You're on the latest version." actually shows after a manual check now — the confirmation used to disappear before it had time to register.

## v1.4.5 — May 2026

### New
- Collapse the sidebar to a slim icon rail for more room — toggle it with ⌘/.
- First launch now opens with a brief animated intro.

### Improved
- Recent activity and any in-progress work now live in one place — the Feed.
- Refreshed the title bar and in-app iconography.

### Fixed
- Recordings are now timestamped when they started, not when transcription finished — so a meeting shows the time it actually happened.
- The notch indicator no longer drifts out of place when you switch a window to full screen.

## v1.4.4 — May 2026

### New
- Reworked first-launch onboarding — clearer setup with a hands-on demo of Solo Mode.
- Press Delete to remove a transcript or speaker, anywhere in History or Speakers.
- Activity feed now logs model downloads, app updates, and onboarding completion — click any row to jump to that recording.

### Improved
- Major UI polish across every page — denser content, unified corner gutter, and the Chirp wordmark now sits in the top-right title bar.
- Update check feels deliberate now — the version pill confirms with a green checkmark that holds long enough to register before fading back.
- Search handles apostrophes correctly — typing "that's" finds the exact word instead of matching anything with the letter "s."
- Search in History is snappy again — instant response while typing.
- History stats live inside the search row and step aside when you search, filter, or select — glanceable the rest of the time.
- Cleaner bulk delete — scope toggle (Text only / Text + audio / Audio only) and Delete share one row, with an X to close.
- Recording badge tells the truth — shows "Mic only" when system audio didn't capture.
- Auto-record meetings — broader app coverage. Now detects calls in WhatsApp, Signal, Telegram, RingCentral, GoTo, Chime, and more (full list in Settings tooltip).
- Speakers page populates reliably on launch — no more manual rescan.

### Fixed
- Meeting recordings are never silently deleted — empty transcripts keep the audio so you can re-transcribe later.
- Other apps' audio keeps playing during Meeting Mode.
- Queue progress shows the real count during bulk re-transcribes — no more "0 of 1" when running multiple jobs.

## v1.4.3 — May 2026

### New
- Time-remaining countdown that learns your Mac's speed.
- Smarter meeting estimates that adapt as Chirp reads the conversation.
- Time-remaining for batches — re-transcribe or recover many files at once.
- Hover any transcript's badge to see how long it took.
- Speed panel on the Models page shows your Mac's transcription speed.
- Storage page rebuilt — cleanup and orphan recovery in one place.
- Cleanup: pick what, when, and how much, with confirmation before deletion.
- Orphan files: filter, sort, preview inline, delete one or all.

### Improved
- Smoother progress bar across the app.
- In-progress queue redesigned to match the rest of the app.
- Menu bar dropdown reordered — Open Chirp is now at the top.
- Activity feed opens with day groups collapsed.

### Fixed
- Confirmation dialogs now name exactly what gets deleted and what stays.
- Speakers page shows every voice on first load — no rescan needed.

## v1.4.2 — April 2026

### Improved
- Tighter karaoke sync — the highlighted word now tracks the spoken audio accurately.
- Audio scrubber stays visible whenever a recording is expanded — drag it before pressing play.
- Dragging the scrubber pauses audio during the drag and resumes on release.
- Tighter History card row with cleaner padding around metadata.

### Fixed
- Pause now keeps your position — the next press resumes from where you stopped, not from the beginning.
- Transcript text no longer flashes during audio playback.
- Transcript text now reads correctly in dark mode.
- Numbers in transcripts now highlight correctly — the digit and the word before it were both losing their highlight.
- Tag pill is now clickable across the full pill, not just the text.
- Play / pause icon stays in the top row whether the card is collapsed or expanded.

## v1.4.1 — April 2026

### New
- Auto-record meetings — start recording automatically when you join a Zoom, Teams, or FaceTime call. Opt-in in Settings.

### Improved
- Smarter media pause — knows the difference between music and a meeting call.
- Cleaner punctuation when you start new sentences mid-dictation.
- Hotkeys activate the moment you grant Accessibility — no restart needed.
- Refreshed Settings page with calmer icons and clearer permission states.
- Speakers page shows the full picture for each profile at a glance.
- Larger hit areas on History card buttons — easier to tap, same look.
- Storage page stays accurate as your library changes.

### Fixed
- Renaming a speaker in one meeting no longer affects your global library.

## v1.4.0 — April 2026

### New
- Powerful history search — combine words with + (AND) and | (OR), wrap phrases in quotes for exact matches.
- Speakers page redesign — confirm or reject any match and the meeting re-scores instantly.
- Storage tab — see what is using disk and manage retention in one place.
- Audio playback unlocked — your recordings are yours, license or not.

### Improved
- Smarter pause formatting in dictation — natural commas mid-thought, ellipses only when you trail off.
- Filters redesigned as inline pills with hover glow.
- Faster panel repositioning after sleep, wake, and display changes.
- License page is more readable and easier to copy from.

### Fixed
- Notch panel repositions correctly across sleep, wake, and display switches.
- Audio scrubber no longer appears on entries that are not playing.
- Rejected meetings collapse with undo instead of vanishing.

## v1.3.2 — April 2026

### Improved
- Media pause is now instant — works with any audio source, including browsers.
- Model downloads continue when Settings is closed.
- Diagnostic reports include media playback state.

### Removed
- Notification for completed meeting transcriptions.

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
