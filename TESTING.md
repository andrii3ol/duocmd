# Testing DuoCmd FREE Preview — 0.4.0-dev Build 127

Thank you for testing! Please read this first.

## Ground rules
1. **Use test data.** Create a folder such as `~/DuoCmd Test` with copies of files, or use a USB drive or disk image you don't need. Don't use the only copy of anything important.
2. Install as described in [README.md](README.md#install), and verify the SHA-256 checksum.
3. Never disable Gatekeeper or System Integrity Protection to run DuoCmd.

## What to try (about 20–30 minutes)

**Basics**
- [ ] Browse both panes. Switch panes with Tab; open folders with Return; go up with ⌘↑ or the ".." row
- [ ] Open, close and lock tabs; quit and relaunch: are your tabs restored?
- [ ] Go to Folder (⇧⌘G), Favorites (add with ⌃⌘T, rename, reorder), filter (⌘F)

**File operations (test folder only)**
- [ ] F5 Copy and F6 Move between panes, one file and several marked files
- [ ] Copy onto an existing name: try each choice (ask, keep both, skip, replace files)
- [ ] F2 Rename, F7 New Folder, F8 Move to Trash (check the item is in the Trash)
- [ ] Copy files in Finder and paste them into DuoCmd (⌘V); Move Items Here (⌥⌘V)
- [ ] Drag files between the panes and from Finder
- [ ] Batch Rename several files with a template such as `photo-[C]`
- [ ] Compress to ZIP, open the ZIP in DuoCmd, extract it

**Viewing and tools**
- [ ] F3 / Quick Look, and View › Open in Viewer for text and hex
- [ ] Find Files (⇧⌘F), with and without Spotlight
- [ ] Checksums, Folder Compare, Find Duplicates
- [ ] F4 on a text file (choose an editor); F4 on a folder (should open the folder in the pane)
- [ ] F9 Open in Terminal, Reveal in Finder (⌥⌘R), Share

**Look and language**
- [ ] All six themes; text size (⌘= / ⌘−)
- [ ] Settings › General › App language, then Relaunch
- [ ] Narrow and wide window sizes

**Especially helpful if you can**
- [ ] macOS 14, 15 or 26, or an Intel Mac
- [ ] VoiceOver, Increase Contrast, Reduce Motion or Reduce Transparency
- [ ] A non-English keyboard layout or input method
- [ ] Native-speaker comments on the translation in your language

## Reporting
Open an issue with the **Bug report** form, or send:
- macOS version and Mac model (Apple silicon or Intel)
- DuoCmd language and theme
- Steps, what you expected, what happened
- A screenshot or screen recording (avoid showing private file names)

If DuoCmd quits unexpectedly, attach the crash report from Console › Crash Reports (look for "DuoCmd").
