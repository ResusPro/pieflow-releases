# PieFlow Custom releases

Public binary distribution channel for Nick's custom Windows builds of [PieFlow](https://github.com/shivankoctupie/pieflow).

The development/build repository remains private. This repository is intended to contain release metadata and finished installers only.

## Editions

- **Standard / Update** — small application-only installer. Reuses an existing persistent local speech runtime when present, or can fall back to a compatible system Python setup.
- **Full Offline** — includes the known-good Python/faster-whisper runtime and Whisper model for first-time/offline installation. The speech runtime is migrated to persistent local application data so later updates can use the Standard installer.

PieFlow is MIT-licensed software by Shivank Goura. See `LICENSE` for the upstream license notice.
