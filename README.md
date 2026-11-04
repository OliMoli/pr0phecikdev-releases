# Pr0phecik Dev - releases

Ready-to-run builds of my apps. This repository holds only finished releases, no source code.

| App | Platform | Latest | Download |
|---|---|---|---|
| **Exosuit** - command center for AI coding agents (Claude Code, Codex, Antigravity, Grok Build, Cursor, local models) on the subscriptions you already have | Windows 10/11 (x64) | <!-- exosuit:version -->0.14.0<!-- /exosuit:version --> | <!-- exosuit:download -->[Exosuit-Setup-0.14.0.exe](https://github.com/OliMoli/pr0phecikdev-releases/releases/download/exosuit-v0.14.0/Exosuit-Setup-0.14.0.exe)<!-- /exosuit:download --> |
| **OmniFetch** - video and music downloader for YouTube, TikTok, Instagram and many other sites, local, no ads, no tracking | Android 8+ | <!-- omnifetch:version -->1.1.0<!-- /omnifetch:version --> | <!-- omnifetch:download -->[OmniFetch-1.1.0.apk](https://github.com/OliMoli/pr0phecikdev-releases/releases/download/omnifetch-v1.1.0/OmniFetch-1.1.0.apk)<!-- /omnifetch:download --> |

All versions: [Exosuit](https://github.com/OliMoli/pr0phecikdev-releases/releases?q=exosuit&expanded=true) · [OmniFetch](https://github.com/OliMoli/pr0phecikdev-releases/releases?q=omnifetch&expanded=true)

## Install and update

- **Exosuit:** download `Exosuit-Setup-x.y.z.exe` and run it. To update, run the newer installer - your settings, sessions and license stay. Exosuit tells you when a new version is out (in the sidebar).
- **OmniFetch:** download `OmniFetch-x.y.z.apk` on the phone and open it (allow installing from your browser once). To update, install the newer APK over the old one - your downloads, library and license stay. OmniFetch shows “A new version is out” when there is one.

Windows SmartScreen may warn about an unknown publisher (the installer is not code-signed yet): **More info → Run anyway**.

## Pro / Premium

Both apps are free. Optional one-time upgrades: [Exosuit Pro](https://prophecik.gumroad.com/l/exosuit) · [OmniFetch Premium](https://prophecik.gumroad.com/l/omnifetch). The license key from the purchase e-mail goes into the app's settings.

## Contact

X: [@Pr0phecikDev](https://x.com/Pr0phecikDev) · pr0phecik.dev@gmail.com

Like the apps? [Buy me a coffee](https://buycoffee.to/pr0phecikdev)

---

<sub>How this repo works: each release is a GitHub Release tagged `<app>-v<version>` with the file attached, and `<app>/latest.json` on `main` is the update feed the apps read (at most every 12 hours). The binary is published first, the feed second, so the apps never point at a missing file.</sub>
