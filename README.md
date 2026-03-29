# Changelog

All notable changes to the CS2 Bind Visualizer will be documented in this file.

## [1.5.0] - Comparison & Layout Enhancements
### Added
- **View Layout Switcher:** Added options for "Auto", "Left/Right" (Side-by-Side), and "Top/Bottom" (Stacked) views.
- **Identification Tags:** Added explicit `[File A]` and `[File B]` labels to headers and modals to distinguish between files with identical names.
- **Enhanced Tooltips:** Tooltips now show the status of both File A and File B simultaneously with colored emoji indicators (🟦, 🟨, 🟩, 🟥).

## [1.4.0] - Commands & Variable Support
### Added
- **Variables Section:** Added a dedicated list for non-bind commands (aliases, cvars, and settings).
- **Command Diffing:** Comparison mode now tracks differences in game variables, not just keybinds.
- **Command Modal:** New modal to edit command names and values separately.
- **Add Command:** Button to inject new variables into the config.
### Fixed
- Restored all international keyboard layouts (Nordic, Dvorak, Colemak, etc.) that were previously missing.

## [1.3.0] - The Sync Update
### Added
- **Cross-File Copy:** Added a "Copy from other config" button inside the keybind modal.
- **Dual-Pane Logic:** Bi-directional copying (Copy from A to B, or B to A).
- **Auto-Save:** Clicking the "Copy" button instantly saves and updates the config.

## [1.2.0] - Comparison Mode
### Added
- **Pane B:** Introduced the second editor and keyboard for comparison.
- **Diff Coloring:** Implemented the color-coded logic for Matches, Conflicts, Additions, and Missing keys.
- **Legend:** Added a visual legend for comparison colors.

## [1.1.0] - Live Editor
### Added
- **Integrated Textareas:** Added live text editors below the keyboards.
- **Live Parsing:** Changes in the text editor update the keyboard visualization instantly.
- **Export System:** Added functionality to download the modified text as a `.cfg` file.

## [1.0.0] - Initial Release
### Added
- **Virtual Keyboard:** Basic visualization of CS2 binds.
- **Layout Support:** Initial QWERTY and AZERTY support.
- **Scancode Mapping:** Support for `scancodeXX` engine names.
- **Tooltips:** Hovering over a key displays the current bind.
