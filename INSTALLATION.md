# Installation and rollback

## Install or replace Remy

1. Download the DMG and matching `.sha256` file from the same GitHub Release.
2. In Terminal, run `shasum -a 256 /path/to/Remy-*.dmg` and compare the result with the published checksum.
3. Open the DMG and drag Remy to Applications.
4. If replacing a beta, quit Remy first, then replace the existing application when Finder asks.
5. Open Remy from Applications and grant only the Reminders, Calendar and notification permissions you want to use.

Remy preferences remain on the Mac when the app is replaced.

## Roll back

1. Quit Remy.
2. Download the earlier signed DMG from its GitHub Release.
3. Verify its checksum, open it and replace Remy in Applications.
4. Reopen Remy and confirm the version in Settings > About.

Preferences are designed to survive a rollback. A rollback must still be tested between every pair of published beta builds; check the release notes before proceeding.

## Uninstall

1. Quit Remy and move `/Applications/Remy.app` to the Trash.
2. Removing the app does not delete or modify reminders stored in Apple Reminders.
3. To remove local Remy preferences as well, contact support for the version-specific cleanup steps. Do not delete unrelated Apple Reminders data.
