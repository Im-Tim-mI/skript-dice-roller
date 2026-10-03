# Dice Roller

**English** | [繁體中文](README.zh-TW.md)

Roll one, two or three six-sided dice; the result is shown to everyone in the same world.

> This repository has two editions of the same script: **繁體中文 (zh-TW)** is the original used on the author's Traditional Chinese server, and **English** is a full translation (commands, messages and variable names) with the same features.

## Features

- Three commands for 1, 2 or 3 dice, with the total
- Results are visible to everyone in the roller's world
- Used by the “More Features” menu of [skript-player-menu-gui](https://github.com/Im-Tim-mI/skript-player-menu-gui)

## Requirements

- [Paper](https://papermc.io/) server (developed on Paper 26.2 / Minecraft 26.2)
- [Skript](https://github.com/SkriptLang/Skript) (developed on 2.16.2)

## Installation

1. Install the plugins listed under [Requirements](#requirements).
2. Download **one** edition:

   | Edition | File(s) |
   |---|---|
   | English | [`en/dice-roller.sk`](en/dice-roller.sk) |
   | 繁體中文 (original) | [`zh-TW/自動化骰子.sk`](zh-TW/%E8%87%AA%E5%8B%95%E5%8C%96%E9%AA%B0%E5%AD%90.sk) |

3. Copy the `.sk` file(s) into `plugins/Skript/scripts/` on your server.
4. Run `/sk reload dice-roller` (use the file name you copied) or restart the server.

> [!IMPORTANT]
> Install **only one** edition. Both editions are the same script in different languages - loading both makes them clash or run twice.

## Commands

| Command (English edition) | zh-TW edition | Description | Permission |
|---|---|---|---|
| `/dice1` | `/一顆骰字` | Roll one die | everyone |
| `/dice2` | `/二顆骰字` | Roll two dice | everyone |
| `/dice3` | `/三顆骰字` | Roll three dice | everyone |

## Related projects

- [skript-player-menu-gui](https://github.com/Im-Tim-mI/skript-player-menu-gui) - Player Menu GUI
- [skript-monopoly-helper](https://github.com/Im-Tim-mI/skript-monopoly-helper) - Monopoly Helper

## License

**MIT + Commons Clause** - see [LICENSE](LICENSE) for the full text.

- ✅ You may use, copy, modify and share this script.
- ✅ You **may** install and run it - including modified versions - on Minecraft servers that charge money or are run for profit.
- ❌ You may **not** sell the script itself or modified versions of it, directly or indirectly, or require payment to obtain its files or source code.

Copyright (c) 2026 廷廷小教室、廷廷的家（Tim945）
