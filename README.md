# JumpNDodge

JumpNDodge is a fast-paced endless dodge/runner game. This repository hosts **compiled release downloads only** — no source code.

## Installing (one-time)

Download the installer once from the **[Installer release](https://github.com/erqf1/JumpNDodge/releases/tag/installer)**:

| File | Platform |
|---|---|
| `JumpNDodge-windows-installer.exe` | Windows |
| `JumpNDodge-linux-installer.run` | Linux |

**Windows**: run the `.exe` and follow the setup wizard. Optionally check "Create a desktop icon". On finish, JumpNDodge launches automatically. This installs to Program Files, adds a Start Menu (and optional desktop) shortcut, and includes an uninstaller.

**Linux**: `chmod +x JumpNDodge-linux-installer.run && ./JumpNDodge-linux-installer.run`, then answer the two prompts (create desktop icon, launch now). This installs to `~/.local/share/JumpNDodge` and adds an entry to your application menu. An `uninstall.sh` is placed in the install folder for removal.

The installer itself never changes between game versions, so you only need it once — see "Staying up to date" below for why.

## Portable, no-install option

Don't want to install anything? Every [versioned release](https://github.com/erqf1/JumpNDodge/releases) also includes a portable `.zip` per platform — a fully self-contained copy of that version. Extract it anywhere (a USB stick, any folder) and run it directly. No installation, no admin rights, no changes to your system.

- **Windows**: extract the zip, run `updater.exe`.
- **Linux**: extract the zip, run `chmod +x updater JumpNDodge`, then `./updater`.

All save data and settings stay inside that same folder, so it's easy to move, back up, or run multiple independent copies side by side.

## Starting the game

However you got JumpNDodge, always launch it via the **updater** (`updater.exe` / `updater`), not the game executable directly.

## Staying up to date

The updater checks GitHub for a newer version every time it starts, updates itself if one is found, and then launches JumpNDodge. This is why the installer above is a one-time download: it just sets up the updater, which then keeps the actual game current on its own. New game versions only ever add a new entry to the [versioned releases](https://github.com/erqf1/JumpNDodge/releases) — the installer isn't touched.


