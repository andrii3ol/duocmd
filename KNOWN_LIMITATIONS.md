# Known limitations — DuoCmd FREE Preview 0.4.0-dev Build 127

## Distribution
- **Not notarized; ad-hoc signed.** macOS blocks the first launch until you allow it in System Settings › Privacy & Security (macOS 15+) or with Control-click › Open (macOS 14). There's no automatic updater; new previews are downloaded manually.
- Settings are stored under the development identifier `com.duocmd.app.dev`.
- The About/Diagnostics panel says "Development build". This build is a preview, not a release.

## Compatibility
- Tested only on **macOS 27.0.1, Apple silicon (M2)**.
- macOS 14.0 (Sonoma), 15 and 26, and Intel Macs, are supported by the build settings (Universal binary, deployment target 14.0) but are **not tested**. Some visual details use newer macOS design features where available and fall back on older systems.

## Not included in this preview
- Archive formats other than ZIP (no RAR, 7z, tar…)
- Network shares discovery, SFTP/FTP/WebDAV and cloud connections
- Permanent delete, merging folders and root/admin mode (by design)
- Editing Finder Tags (tags are shown, not edited)
- Quick Open command palette, temporary shelf
- Background operation queue (one file operation runs at a time)

## Safety notes
- Crash safety of copy/move is tested. Power-loss safety is not.
- Move within one disk is a rename. Across disks, items are copied and verified first; then the originals go to the Trash on their own disk.
- After an interruption, DuoCmd lists unfinished operations at the next launch but does not change anything automatically.
- If another app changes a file while DuoCmd is working on it, DuoCmd detects most such changes and stops, but can't prevent every race. Avoid folders under active sync or build.

## Keyboard and accessibility
- On most Mac keyboards the F-keys need **Fn**, or turn on "Use F1, F2, etc. keys as standard function keys" in System Settings › Keyboard.
- The internal Viewer has no default key in the Mac layout; it's in the View menu. The Commander layout puts it on F3, and you can add a key in Settings › Keyboard.
- VoiceOver labels are implemented, but full VoiceOver, Reduce Motion/Transparency and Increase Contrast testing by hand is still pending.

## Languages
- Translations other than English are machine translations and haven't been reviewed by native speakers yet. Corrections are welcome.
