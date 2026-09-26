# Manyhands: downloads

Installers for the Manyhands desktop app, and the `latest.json` an installed copy polls to update
itself. Nothing else lives here. The app's source is in a private repository.

**Install once:** open the newest release under Releases and run `Manyhands_<version>_x64-setup.exe`.
Windows SmartScreen says unrecognised app; choose More info, then Run anyway. The installer is not
code-signed with a Microsoft certificate; it is signed with Pavilion's own update key, which the
app checks before applying any update.

**After that** the app updates itself: it checks here when it starts and every six hours, and
offers the new version as a card. Settings > About has Check for updates.
