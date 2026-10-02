# Hushtrail

Clear selected app history. Review possible uninstall leftovers.

**[Download Hushtrail 0.1.3 for Mac](https://github.com/JaminZhou/hushtrail-releases/releases/download/v0.1.3/Hushtrail-0.1.3.zip)** · [Release notes](https://github.com/JaminZhou/hushtrail-releases/releases/tag/v0.1.3) · [Website](https://jaminzhou.com/hushtrail/)

This repository hosts official downloads, release notes and public issue reports. It does not contain the application source code.

## Install

Requires macOS 27.0 or later. Unzip the download and drag **Hushtrail.app** to **Applications**. The app is Developer ID signed and notarized by Apple. The ZIP contains a stapled app; SHA256SUMS.txt accompanies each release.

For updates, quit Hushtrail and replace it with the new download. There is no automatic updater. Do not disable Gatekeeper or remove quarantine to work around a warning; download a fresh official copy or contact support.

## What it does

- **App Cleanup** remembers apps you choose and detects standard system recent-document lists before app-specific history. Finder Recent Folders and IINA playback history are separate capabilities.
- **Leftovers** scans standard locations only after you click Scan. It checks current apps, registrations and components; you review and select candidates before moving them to system Trash.
- Caches/logs and app data/settings have separate bulk actions. Application Support may contain personal files and needs an exact-directory confirmation.
- Native English and Simplified Chinese UI, system language preferences, and system/light/dark appearance.

No browser history or cookies, startup scan, whole-disk sweep, app-managed backup/restore, or automatic emptying of Trash. History removal can be irreversible; original documents and media are kept. Items in Trash still occupy storage until removed by you.

## Compatibility and permissions

Initial real-machine validation used macOS 27.0 (26A428) on Apple silicon. The app includes arm64 and x86_64 code; Intel hardware acceptance is not claimed.

Finder Recent Folders and the separate **experimental** Recents in Chosen Folders no longer require an exact macOS version. The app retains its macOS 27.0 minimum; actual storage format, file identities, recent-use metadata and safety checks determine availability. OS updates alone do not disable these features. Tested system versions remain evidence, not a guarantee that every newer system has passed real-machine acceptance.

System Recent Documents supports detected `.sfl4` archives. It clears the selected system list, not every app-owned history or every Dock menu; applications can maintain or recreate their own history. Artificial A/B menu/restart checks passed; Preview/Dock-specific cleanup and the system administrator-dialog Cancel branch remain outside completed acceptance.

Finder Recent Folders normally quits and reopens Finder. Close all Finder windows/tabs and finish file operations first; windows are not restored. Experimental chosen-folder Recents temporarily moves eligible local files for Spotlight verification. Save and close files first; clouds/sync folders, packages, links and other disks are excluded. Follow any interruption-recovery prompt.

Full Disk Access may be needed for app histories; macOS can separately request an administrator password for a targeted list reset or an explicitly requested read-only component check. Hushtrail installs no privileged helper and does not enable privacy permissions for you. Local development-build permissions may need reconfirmation for the distributed app.

Leftover candidates do not prove uninstall or exclusive ownership. Unknown vendor/friendly-name folders, whole containers, shared groups, drivers, services, foreign-owned files and unverified trees are kept with reasons. Only standard, validated locations are eligible.

## Support and privacy

[Support guide](https://jaminzhou.com/hushtrail/support/) · [Privacy policy](https://jaminzhou.com/hushtrail/privacy/) · [English feedback form](https://tally.so/r/rj7WXL) · [Email](mailto:me@jaminzhou.com)

GitHub Issues are public. Do not include private paths, documents, history, credentials or logs containing those details. Use email for private questions. In-app support shares only the visible version/app metadata when you choose to open the form or an editable email draft; it never auto-submits a report.

Copyright © 2026 JaminZhou. All rights reserved.
