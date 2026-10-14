# playnite-tui

A clean, terminal-inspired desktop theme for [Playnite](https://playnite.link/) based on the **system24** / [discord-tui](https://github.com/chakibchemso/discord-tui) aesthetic.

![Theme Preview](Images/applogo.png)

---

## Features

- **TUI-Framed Layout**: Sharp 1px bordered boxes with embedded top-border terminal headers:
  - `menu` — Top navigation, search, and view switcher
  - `nav` — Compact sidebar with controller & library navigation
  - `games` — Channels list for your game library
  - `info` — Game overview, metadata badges, and media
- **Zero Rounded Corners**: True terminal look with `0px` border radius across all windows, buttons, badges, and controls.
- **Monospace Typography**: Clean coding font stack (`Consolas`, `Cascadia Mono`, `DM Mono`).
- **Discord Channel Aesthetic**: Game items prefixed with `#` in vibrant pastel purple (`#B396E8`).
- **Discord Embed Descriptions**: Notes and descriptions styled with vertical accent bars, matching Discord rich embeds.
- **Uniform 10px Grid**: Strict, pixel-perfect alignment across all panels and window edges.
- **Accurate system24 Color Palette**:
  - Main Window: `#141414` (oklch 19%)
  - Panel Backgrounds: `#1D1D1D` (oklch 23%)
  - Controls & Buttons: `#262626` (oklch 27%)
  - Borders: `#303030` (oklch 31%)
  - Primary Accent: `#B396E8` (Purple)
  - Secondary Accent: `#1DBEC5` (Cyan)
  - Notifications / Pings: `#E586A5` (Pink)
  - Success / Installed: `#5ABF8D` (Green)

---

## Installation

### Method 1: Using `.pthm` Package (Recommended)

1. Download the latest `PlayniteTUI_*.pthm` file from the [Releases](https://github.com/icymarsh/playnite-tui/releases) section.
2. Drag and drop the `.pthm` file into the Playnite window (or double-click it while Playnite is installed).
3. Confirm installation and restart Playnite.
4. Go to **Settings** (`F4`) ➔ **Appearance** ➔ **General** ➔ select **playnite-tui**.

### Method 2: Manual Installation (Git)

1. Navigate to your Playnite Themes directory:
   - **Installed version:** `%AppData%\Playnite\Themes\Desktop\`
   - **Portable version:** `<PlayniteDirectory>\Themes\Desktop\`
2. Clone this repository:
   ```bash
   git clone https://github.com/icymarsh/playnite-tui.git PlayniteTUI
   ```
3. Restart Playnite and select **playnite-tui** in **Settings ➔ Appearance ➔ General**.

---

## Recommended Settings

For the most faithful TUI experience:
- **Font**: Ensure you have `Cascadia Mono`, `Consolas`, or `DM Mono` installed.
- **View**: Details View (`Ctrl + 1`) provides the closest match to discord-tui channel/chat layout.

---

## Credits & Acknowledgements

- **[refact0r](https://github.com/refact0r)** — Creator of the original [system24](https://github.com/refact0r/system24) theme.
- **[chakibchemso](https://github.com/chakibchemso)** — Creator of [discord-tui](https://github.com/chakibchemso/discord-tui).
- **[JosefNemec](https://github.com/JosefNemec)** — Creator of [Playnite](https://github.com/JosefNemec/Playnite).

---

## License

This project is licensed under the [MIT License](LICENSE).
