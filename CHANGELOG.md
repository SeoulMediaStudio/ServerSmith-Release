# Changelog

All notable changes to ServerSmith are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.1] - 2026-05-29

A small update that adds a Reset token option.

### Added
- Setup → Reset token… removes the saved bot token from your PC (a clean
  "sign out"). Useful when switching bots or before handing the computer to
  someone else. Your token lives in the Windows Credential Manager, so this is the
  supported way to clear it.

  [0.1.1]: https://github.com/SeoulMediaStudio/ServerSmith-Release/releases/tag/v0.1.1

## [0.1.0] - 2026-05-29

First public release.

### Added
- One-click building of a fully configured Discord server: roles, categories,
  channels (text, voice, stage, forum), permission overwrites, forum tags and
  starter posts, seed messages, and member role grants.
- Visual editors for server settings, roles (colour, hoist, mentionable,
  permissions, drag-to-reorder hierarchy), categories and channels, and
  onboarding.
- Six built-in templates: Friends/Hangout, Hobby/Club, Community, Gaming,
  Creator/Streamer, and Dev Studio/Product. Templates can be duplicated, edited,
  imported (file or URL), and exported as shareable bundles.
- Preview (dry-run) and a "Preview changes" diff so you can see exactly what a
  build would create, update, rename, or skip before it runs.
- Live, colour-coded build log with timestamps, a progress bar, a post-build
  summary, and a copy-log button.
- Per-step retry on transient network errors for more reliable builds.
- Update-only builds by default; the destructive wipe option is gated behind a
  clear double confirmation.
- Full builds without Discord Community enabled; Community-only features are
  labelled and skipped gracefully when it is off.
- Secure bot-token storage via the Windows Credential Manager.
- Multiple connection profiles for managing several bots/servers.
- Built-in update checking with one-click install that preserves your data.
- English and German interface.

[0.1.0]: https://github.com/SeoulMediaStudio/ServerSmith-Release/releases/tag/v0.1.0
