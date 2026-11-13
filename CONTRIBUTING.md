# Contributing to mac-mastery

Thanks for wanting to make Mac users more productive! This repo lives or dies by its shortcuts, so every contribution helps someone stop hunting for the right key.

## How to add a shortcut

Every shortcut row follows this exact format:

\| Keys | What it does | Level | Memory hook \|

Example:

\| ⌘ ⇧ 4 | Screenshot a selected area | Power User | "4 draws a box like a spy with a magnifying glass" \|

### Keys column
Use real macOS symbols: **⌘ ⌥ ⌃ ⇧ ⎋ ⌫ ⏎ ⇥**. Combine them with spaces, e.g. `⌘ ⌥ V`. Don't write "Cmd" or "Ctrl" — use the symbols.

### Level column
Pick exactly one: **Beginner**, **Power User**, or **Wizard**.

- **Beginner:** daily-driver shortcuts everyone should know
- **Power User:** saves serious time, slightly less obvious
- **Wizard:** hidden, obscure, or terminal-level magic

### Memory hook column
One short, funny, or visual sentence that helps someone remember the shortcut. Be silly — the weirder, the stickier. Each hook must be unique within its folder.

## Tone guidelines

- **Friendly:** write like you're helping a friend at a coffee shop
- **Funny:** a dad joke beats a dry definition
- **Short:** no paragraphs. If it doesn't fit in a glance, trim it
- **No filler:** every line should teach or amuse

## Accuracy

Only include shortcuts that really work on macOS. Test on your Mac before submitting. If a shortcut depends on a macOS version, keyboard layout, or app, say so in the row or folder intro.

## Pull Request Checklist

- [ ] The shortcut actually works on my Mac
- [ ] Row format matches `\| Keys | What it does | Level | Memory hook \|`
- [ ] Modifier keys use real symbols (⌘ ⌥ ⌃ ⇧ ⎋ ⌫ ⏎ ⇥)
- [ ] Memory hook is unique and memorable
- [ ] Folder README has an intro, a table, and a "Try it now" challenge
- [ ] I tested the shortcut on my macOS version and noted any version caveats

## How to submit

1. Fork this repo
2. Create a branch: `git checkout -b add-my-shortcut`
3. Add or edit the folder README
4. Commit with a clear message (e.g. `Add ⌘ ⇧ 4 screenshot shortcut to 01-basics`)
5. Open a pull request

We review PRs quickly and always leave a :tada: when we merge.
