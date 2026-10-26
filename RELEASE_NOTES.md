# DuoCmd FREE Preview — 0.4.0-dev Build 127

**Pre-release for testing.** Ad-hoc signed, **not notarized**. Not production software.

## Download

| File | Size | SHA-256 |
|---|---|---|
| `DuoCmd-FREE-Preview-0.4.0-dev-b127.dmg` | 7,422,565 bytes (7.1 MB) | `9e555b5f3c9f2d33c63ec53abedccaefaee2521c1919918a2f2276042a7e9b77` |

Verify before opening:
```
shasum -a 256 DuoCmd-FREE-Preview-0.4.0-dev-b127.dmg
```

- **App:** DuoCmd 0.4.0-dev (127), Universal (arm64 + x86_64), minimum macOS 14.0
- **Source revision:** `213e5a5`
- **App executable SHA-256:** `a2ad681b16b2321c622f46fec7071cf86937f587d541fa6d59c8bf602489d817`

## What's in this build

The first public preview of DuoCmd FREE: a native, keyboard-first, dual-pane file manager.

- **Dual panes** with tabs, tab lock, session restore, path bar, Go to Folder (⇧⌘G), editable Favorites and a type-to-filter box (⌘F)
- **Function-key workflow:** F2–F8 for Rename, View, Edit, Copy, Move, New Folder and Trash; F9 for Terminal. Mac or Commander key layout, and a shortcut editor with conflict checking.
- **Careful file operations:**
  - Copies are verified before they get their final name.
  - Nothing is deleted permanently, and folders are never merged or replaced.
  - System folders and disks are protected.
  - Conflict choices: ask, keep both, skip, or replace files (the old version goes to the Trash).
- **Clipboard paste** (copy or move) and **drag-and-drop** between panes
- **Batch Rename** with live preview
- **ZIP** browse, extract and create
- **Checksums** (SHA-256, SHA-1, MD5), **Folder Compare** and **duplicate finder**; the last two only mark files
- **Viewing and search:** Quick Look and a read-only Text/Hex viewer; Find Files (folder walk or Spotlight) with a results pane
- **Inspector and Get Info**, configurable columns, folder sizes
- **Six themes** and user themes, adjustable text size
- **Ten languages** with an in-app picker: en, nl, uk, de, fr, es, it, pt, pl, ja

## Verification done for this build

- 528 automated tests pass in both Debug and Release builds, with no skipped tests and no compiler warnings. Packaging checks: 20/20.
- A separate, independent targeted code review of the final changes reported no blocking findings in its audited scope. This is not a security certification.
- The DMG was mounted and checked; the app's signature verified; it was installed to a temporary location and launched and quit on macOS 27.0.1 (Apple silicon).

## Not verified yet

- macOS 14, 15 and 26, and Intel Macs (supported by the build, not yet tested)
- Hands-on checks of VoiceOver, accessibility display settings, physical keyboards with Fn keys, input methods for non-Latin languages, drag-and-drop and clipboard paste
- Native-speaker review of the nine translations

See [KNOWN_LIMITATIONS.md](KNOWN_LIMITATIONS.md).
