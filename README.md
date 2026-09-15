# Ayu CloudStream Games

Interactive retro emulation runtimes and classic homebrew engine plugins for CloudStream 3.

## Installation

Add this repository in **CloudStream 3** (Settings > Extensions > Add Repository):

- **Shortcode**: `CSGAMES`
- **Repository URL**:
```text
https://raw.githubusercontent.com/errorcode26/Ayu-CloudStream-Games/builds/repo.json
```

## Architecture & Features

- **Game Boy Advance Runtime**: High-fidelity gbajs WebAudio engine with DirectSound DMA FIFO priming, 60.0988 Hz hardware frame pacing, and 4-layer atomic state persistence.
- **NES Runtime**: JSNES emulation engine with APU audio register shadowing, channel enable preservation, and atomic battery save management.
- **Classic WebAssembly / Canvas**: Lightweight, standalone HTML5 game runtime engines with touch overlay controls.

## Disclaimer & DMCA

This repository is strictly for educational, non-commercial research demonstrating embedded WebAssembly and Canvas emulation runtimes inside Android WebView environments. All console trademarks and copyrights belong to their respective holders. No commercial distribution is operated or endorsed.

To request prompt removal of any material, open an issue marked `[DMCA]` or contact the maintainer directly.

## License

GNU General Public License v3.0
