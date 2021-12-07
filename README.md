# Tressel Sync for Obsidian

Official Tressel plugin to sync/export your tweets and threads from [Tressel](https://tressel.xyz) into Obsidian

## Instructions

1. Install the plugin
2. Copy your personal token from the Obsidian settings section in the [Tressel app](https://app.tressel.xyz) into the Tressel plugin settings in Obsidian
3. **You're done!** Your tweets & threads will automatically be synced every time you open Obsidian
4. *Optional - you can click the Sync Tressel button in the side ribbon to manually sync from Tressel*
5. *Optional - you can click Clear Sync Memory in the plugin settings to resync all your tweets/threads from scratch*

## Notes

*The plugin is in the **alpha** stage of development and has currently only been tested on desktop*

For feature requests, to report bugs or request help using the plugin, use the Help & Support form in the [Tressel app](https://app.tressel.xyz)

## Changelog

- 0.1.0
  - Adds images to synced tweets and threads from Tressel
  - Internal improvements:
    - Use Obsidian Vault API instead of Adapter API
    - Use Obsidian request API instead of axios (for greater mobile compatibility and smaller bundle size)
    - Use async/await instead of .then (for better code readability)
- 0.0.2
  - Restricts the plugin for desktop use only (due to lack of testing on mobile)
- 0.0.1
  - Initial release
  - Sync your tweets and threads from Tressel to Obsidian (text-only)