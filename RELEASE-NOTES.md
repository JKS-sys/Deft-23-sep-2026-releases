# Deft release notes

Newest first. Downloads: https://github.com/JKS-sys/Deft-23-sep-2026-releases/releases/latest · https://ipconfig.co.network/deft

## Deft 0.1.1 — 08 Nov 2026

- One-command release: `bash update.sh` (keys from the dashboard vault) builds, signs, writes the notes and publishes to GitHub and R2; `npm run build:mac:arm64` makes a local app and DMG.

- By App: pick any app and make it the default for everything it opens — or one category of it — in one go.
- Health: finds defaults whose app is gone or in the Trash, types with no default, siblings that disagree (.jpg and .jpeg, http and https) and apps installed twice, with Fix all.
- Activity with Undo: every change remembers what it replaced, shown as a coloured log box; Undo puts back exactly that.
- Your Choices: every default this Mac's user has set, read straight from Launch Services.
- Try it: opens a real sample file (PNG, PDF, SVG, Markdown…) so you see the new default app at once.
- Drop any file on the window to see and change what opens it.
- 19 categories and over 350 types: RAW photos, subtitles, eBooks, web development, shell scripts, databases, fonts, disk images, design and 3D, Apple developer files — plus any type you add yourself.
- Six list layouts, four window layouts, compact density, a command palette (⌘K) and right-click menus on every row.
- Every action has its own sound and its own self-drawing animation; Motion Off / Subtle / Lively and ten sound packs.
- More colour everywhere — every category, page, kind and status has its own hue, numbers, brackets and extensions are coloured, and there is no pink anywhere.
- Deft Pro through your ipconfig account (sign in with a password or an emailed code): profiles, import and restore. ₹20 a month or ₹220 a year.
- Crash reports: a problem is written down and Deft asks at the next start whether to send it; nothing leaves without a yes.
- Owner Panel on the owner's Mac: make codes, revoke, extend, email them; subscriptions, crashes, installs and computers with bulk actions and export.
- Updates check the public GitHub release first, then its mirror, then ipconfig.co.network.

### Install

Deft is a Mac app (Apple silicon — M1 and later). One download: `Deft_<version>_aarch64.dmg`.

- **With Pour:** `curl -fsSL https://ipconfig.co.network/pour/install | sh` then `pour install --cask deft`
- **By hand:** open the DMG and drag Deft into Applications. First launch: `xattr -cr /Applications/Deft.app` (Deft is self-signed, not notarized).
- Per-app volume and the equaliser need macOS 14.4 or later.
- Earlier Windows, Linux, ChromeOS, FreeBSD and Intel Mac builds stay on the releases page but are no longer updated.
