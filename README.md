# JumpNDodge

JumpNDodge is a fast-paced endless dodge/runner game. 
## Downloads

Grab the latest release from the [Releases page](https://github.com/erqf1/JumpNDodge/releases). Each release includes four files:

| File | Platform | Type |
|---|---|---|
| `JumpNDodge-<version>-windows-installer.exe` | Windows | Installer |
| `JumpNDodge-<version>-linux-installer.run` | Linux | Installer |
| `JumpNDodge-<version>-windows.zip` | Windows | Portable archive |
| `JumpNDodge-<version>-linux.zip` | Linux | Portable archive |

You only need **one** of these per platform: the installer for a proper setup, or the archive if you'd rather run it portably.

## Using the installer

**Windows** (`...-windows-installer.exe`)
1. Run the `.exe` and follow the setup wizard.
2. Optionally check "Create a desktop icon".
3. On finish, JumpNDodge launches automatically.

This installs to Program Files, adds a Start Menu (and optional desktop) shortcut, and includes an uninstaller.

**Linux** (`...-linux-installer.run`)
1. Make it executable: `chmod +x JumpNDodge-*-linux-installer.run`
2. Run it: `./JumpNDodge-*-linux-installer.run`
3. Answer the two prompts (create desktop icon, launch now).

This installs to `~/.local/share/JumpNDodge` and adds an entry to your application menu. An `uninstall.sh` is placed in the install folder for removal.

## Using the portable archive

The `.zip` for your platform is not just a fallback — it's a fully self-contained, portable copy of JumpNDodge. Extract it anywhere (a USB stick, any folder, wherever) and run it directly. No installation, no admin rights, no changes to your system.

- **Windows**: extract the zip, run `updater.exe`.
- **Linux**: extract the zip, run `chmod +x updater JumpNDodge`, then `./updater`.

All save data and settings stay inside that same folder, so it's easy to move, back up, or run multiple independent copies side by side.

## Starting the game

Whether installed or portable, always launch via the **updater** (`updater.exe` / `updater`), not the game executable directly. The updater checks GitHub for a newer version on every start, updates itself if one is found, and then launches JumpNDodge — this is how you get fixes and new content without manually redownloading anything.


