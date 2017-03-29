# vscode-case-sensitive-add-next README

This extension replaces the keybinding for "Add Next Occurrence" with a similar command that is always case-sensitive. It's pretty quick and dirty; I just needed to write something to do this to keep myself sane working with Code.

## Features

See description. There's not much to it. :)

## Requirements

VSCode >= 1.1.0

## Extension Settings

Nothing aside from its keybinding.

## Known Issues

- None known, but I'm sure there's plenty that are unknown.

## Release Notes

### 0.0.4

- Using command when selections don't have matching content now does nothing (like existing Add Next Occurrence command).
- New selections now get focus if they're outside of the current view.

### 0.0.3

- Fix for behavior when multiple selections exist that have different content.
- Changed default keybinding so it doesn't clobber existing Add Next Occurrence command.

### 0.0.2

- Fixed extension only selecting instances after the last selected instance.

### 0.0.1

- Initial release!