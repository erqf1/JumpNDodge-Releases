# JumpNDodge Archive

JumpNDodge is a fast-paced endless dodge/runner game. This repository hosts **every version as a portable, no-install download** — no source code.

Want the easy route instead? Get the one-time installer from **[erqf1/JumpNDodge](https://github.com/erqf1/JumpNDodge)** — it sets up the game and its self-updater, so you never have to come back here manually.

## Downloads

Grab any version from the [Releases page](https://github.com/erqf1/JumpNDodge-Archive/releases). Each release includes:

| File | Platform |
|---|---|
| `JumpNDodge-<version>-windows.zip` | Windows |
| `JumpNDodge-<version>-linux.zip` | Linux |

## Using the portable archive

Extract the zip for your platform anywhere (a USB stick, any folder) and run it directly. No installation, no admin rights, no changes to your system.

- **Windows**: extract the zip, run `updater.exe`.
- **Linux**: extract the zip, run `chmod +x updater JumpNDodge`, then `./updater`.

All save data and settings stay inside that same folder, so it's easy to move, back up, or run multiple independent copies side by side.

## Starting the game

Always launch via the **updater** (`updater.exe` / `updater`), not the game executable directly. The updater checks this repository for a newer version every time it starts, updates itself if one is found, and then launches JumpNDodge.

## Source code

This repository intentionally contains only compiled binaries. JumpNDodge's source code is developed in a private repository.
