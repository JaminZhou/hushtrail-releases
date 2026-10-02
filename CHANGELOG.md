# Changelog

## 0.1.3 — 2026-10-02

- Keep Finder Recent Folders and experimental Recents in Chosen Folders available after macOS updates by removing the exact 27.0.0 version gate.
- Check the actual history format, file identity and recent-use metadata while retaining normal quit/reopen, execution-time revalidation, index verification and interruption recovery.
- Explain unsupported Finder history formats directly and update the Recents help in English and Simplified Chinese.

Requires macOS 27.0 or later. This removes a version-label restriction; it does not establish real-machine acceptance for every newer macOS release. The chosen-folder feature remains experimental.

## 0.1.2 — 2026-09-30

- Fix skipped Recents records caused by filename-based Spotlight verification, including records inside subfolders.
- Remove the 2,000-item and 20-record limits and the whole-check deadline. Check all discovered records in the selected folders and subfolders; cancellation and per-command timeouts remain available.
- Explain folder access failures and distinguish incomplete Spotlight queries, missing index results, and inconsistent recent-use metadata.
- Keep the chosen-folder sheet compact after adding and removing folders.

The chosen-folder Recents capability remains experimental. Original files are retained; file safety checks, execution-time revalidation and interruption recovery remain in place.

## 0.1.1 — 2026-09-28

- Keep the Choose Again button below an unavailable folder’s status, aligned with its name and location.
- Size the chosen-folder list to its content, with scrolling for longer lists, so reselection buttons remain visible.
- Cleanup behavior and compatibility requirements are unchanged.

## 0.1.0 — 2026-09-27

Initial independently distributed Hushtrail release.

- Remember selected apps and check standard system recent-document lists.
- Clear Finder Recent Folders and compatible IINA playback history as separate selections.
- Provide an explicitly labeled experimental Recents-in-chosen-folders flow.
- Discover generic uninstall-leftover candidates in standard caches, logs, preferences, identifier-named app data and verified individual container caches/logs.
- Review grouped selections, use separate category bulk actions, and see why items are kept.
- Move selected leftovers to system Trash; no private backup/restore or Trash emptying.
- English/Simplified Chinese, system/light/dark appearance, and email/Tally support.

Requires macOS 27.0 or later; Finder capabilities are currently limited to macOS 27.0.0. See README for tested scope, permissions and remaining compatibility gaps. This release is Developer ID signed and notarized; notarization is not an Apple endorsement of cleanup behavior.
