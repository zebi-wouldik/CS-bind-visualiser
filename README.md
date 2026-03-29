# Ultimate CS2 Bind & CFG Editor

A powerful, browser-based visual editor for Counter-Strike 2 configuration files (.cfg). This tool allows users to visualize their keybinds on a virtual keyboard, manage game variables, and synchronize/compare two different configuration files in real-time.

## 🚀 Features

### ⌨️ Visual Keyboard
- **Multiple Layouts:** Supports QWERTY (US/UK), AZERTY (FR/BE), QWERTZ (DE), Spanish, Nordic, Dvorak, Colemak, and Workman.
- **Visual Feedback:** Keys are highlighted based on their status (Bound, Unbound, Conflict, or Added).
- **Interactive Editing:** Click any key to change its bind or unbind it directly.

### 📋 Command & Variable Management
- **Beyond Binds:** Automatically parses and lists all non-bind commands (e.g., `fps_max`, `sv_cheats`, `alias`).
- **Structured Editing:** Modify the command name and value separately in a clean interface.

### ⚖️ Live Comparison (Diff Mode)
- **Dual Pane View:** Load two configs side-by-side (e.g., your `autoexec.cfg` and a pro player's config).
- **Smart Highlighting:**
  - **Match (Blue):** Identical binds/values in both files.
  - **Conflict (Yellow):** Same key/command but different values.
  - **Added (Green):** Key/command exists only in the current file.
  - **Missing (Red/Dashed):** Key/command exists only in the other file.
- **One-Click Sync:** Instantly copy binds or variables from one config to the other using the "Copy from other" button.

### 🛠 Ergonomics
- **Flexible Layouts:** Switch between "Auto", "Side-by-Side", or "Stacked" views.
- **File Integrity:** Generates clean `.cfg` code with `unbind` safety and preserves comments where possible.
- **Client-Side:** All processing happens in your browser. Your files are never uploaded to a server.

## 🖥 How to Use
1. Open `index.html` in any modern web browser.
2. **Load:** Click "Choose File" or paste your config text directly into the editors.
3. **Edit:** Click keys on the keyboard or items in the command list.
4. **Compare:** Enable "Compare Mode" to open the second pane.
5. **Export:** Click "Export File" to download your modified `.cfg`.
