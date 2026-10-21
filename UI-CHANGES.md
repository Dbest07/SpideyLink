# UI Changes (preview)

Applied to `src/ui/index.tis` and `src/ui/index.css`:

- Removed the Collaborators + encrypted files panel (`<SpideyAccess />`) from the main window.
- Simplified the right pane to a clean connect card + compact updates card.
- Darker professional theme with spider-red accents (`#ff4d6d`).
- Larger, clearer connection code display.
- Update check button and status remain functional (existing `spidey_update` background check + pending apply is unchanged).

Rebuild the Windows binary from the private development tree after applying these files, then upload only the new `.exe` to a release.
