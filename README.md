<p align="center">
  <img src="assets/serversmith_logo.svg" alt="ServerSmith — Forge your server in one click." width="560">
</p>

<p align="center"><strong>English</strong> · <a href="README.de.md">Deutsch</a></p>

ServerSmith is a Windows desktop app that lets <em>anyone</em> design and create a
fully configured Discord server — roles, categories, channels, permissions,
forums, and onboarding — at the press of a button. No terminal, no PowerShell,
no code editing. It ships with reusable templates, stores everything locally,
and guides non-technical users with built-in help.

---

## Download

**[Download the latest release »](https://github.com/SeoulMediaStudio/ServerSmith-Release/releases/latest)**

Grab `ServerSmith-Setup-<version>.exe` from the latest release and run it.

## Features

- **Visual editors** — design roles (colours, hoist, mentionable, permissions),
  categories, and channels (text, voice, stage, forum) with per-channel topics,
  slow-mode, permission overwrites, forum tags, and starter posts.
- **Ready-made templates** — six built-in starting points (Friends/Hangout,
  Hobby/Club, Community, Gaming, Creator/Streamer, Dev Studio/Product), plus your
  own. Import and export setups to share them.
- **Preview before you build** — a dry run shows exactly what will be created or
  changed before anything touches your server.
- **Live build log** — watch progress in real time with clear, friendly messages
  and a copy-log button.
- **Safe by default** — update-only builds never delete anything; the wipe option
  is hidden behind a clear double confirmation.
- **Discord Community optional** — full builds work without it; Community-only
  features (stage channels, onboarding, announcement channels) are clearly
  labelled and skipped gracefully when it's off.
- **Secure** — your bot token is stored in the Windows Credential Manager, never
  in plaintext or in the app's database.
- **Stays up to date** — checks for new versions on launch and installs them in a
  click (your templates and settings are preserved).
- **English & German** — switch the interface language at any time.

## System requirements

- Windows 10 or 11 (64-bit)
- A Discord account and a bot token (the app walks you through creating one)

## Installation

1. Download `ServerSmith-Setup-<version>.exe` from the
   [latest release](https://github.com/SeoulMediaStudio/ServerSmith-Release/releases/latest).
2. Run the installer. It installs per-user, so no administrator rights are needed.
3. Launch **ServerSmith** and follow the first-run setup to connect your bot and
   pick your server.

> **Note:** Because the installer is downloaded from the internet, Windows
> SmartScreen may show a prompt on first run. Choose **More info → Run anyway** to
> continue.

## Updating

ServerSmith checks for updates automatically when it starts. When a new version
is available you'll see what's new and can install it in one click — your saved
templates, profiles, and settings are kept. You can turn the automatic check off
under **Help → Check for updates on start**, or check manually any time via
**Help → Check for updates…**.

## Verifying your download (optional)

Each release includes a `SHA256SUMS` file. To confirm your download is intact,
run in PowerShell:

```powershell
(Get-FileHash -Algorithm SHA256 .\ServerSmith-Setup-<version>.exe).Hash
```

and compare the result (case-insensitive) with the matching line in `SHA256SUMS`.

## Getting started

After installing, open ServerSmith and the built-in guide walks you through:

1. Creating a bot and pasting its token (stored securely on your PC).
2. Inviting the bot to an empty server you created.
3. Picking a template (or building your own), previewing, and clicking **Build**.

The in-app **Help** tab covers everything in detail.

## Support

Questions, feedback, or issues? Email **info@seoulmediastudio.com** or open an
issue in this repository.

## License

Copyright © 2026 **Seoul Media Studio**. All rights reserved. See
[`LICENSE.txt`](LICENSE.txt).
