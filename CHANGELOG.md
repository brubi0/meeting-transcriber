# Changelog

All notable changes to Meeting Transcriber will be documented in this file.

## [0.56] - 2025-11-12

### Added
- 🎙️ **Voice Note Recorder** - Record quick voice notes with press-and-hold button
  - Listen to recording before transcribing
  - Perfect for capturing ideas on the go
  - Works great on mobile devices
- 📱 **iOS/Safari Compatibility** - Fixed audio recording on iPhone and Safari
  - Auto-detects iOS and uses compatible audio codecs (mp4 instead of webm)
  - Improved mobile responsive design
  - Better touch interactions for mobile
- 📱 **Mobile Optimizations**
  - Responsive CSS for phone screens
  - Larger touch targets for buttons
  - Better layout on small screens
  - Auto-hide tab recording on mobile (not supported)
  - PWA meta tags for "Add to Home Screen"

### Fixed
- iOS Safari microphone recording now works properly
- Audio codec compatibility issues on mobile browsers
- Touch event handling for mobile devices

### Changed
- Version number now displayed in footer
- Updated last modified date
- GitHub link in footer

## [0.55] - 2025-11-11

### Added
- Initial release with core features
- Real-time microphone transcription
- Browser tab recording with audio capture
- File upload transcription (audio/video files)
- Save and export transcripts
- AI analysis prompt generation (for use with Claude/ChatGPT)
- English/Spanish multilanguage auto-detection
- Local storage for transcripts
- GitHub Pages deployment

### Features
- 🎤 Microphone recording
- 🖥️ Browser tab recording (desktop only)
- 📤 File upload (MP3, WAV, MP4, etc.)
- 💾 Save transcripts locally
- 📥 Export transcripts as text files
- ✨ Export with AI analysis prompts
- 🌐 Works offline (after initial load)

---

## Version Numbering

- Increment by 0.01 for each update
- Format: 0.XX
- Current: v0.56
