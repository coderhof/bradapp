# BradApp

BradApp is a lightweight, installable web app for planning meals and keeping a recipe book. The app includes all 190 built-in recipes by default, plus a navy/cream app icon.

## Updates in this build
- Grocery ingredient quantities scale with the selected **People / servings** value. Standard numeric, decimal, mixed-fraction, and common Unicode-fraction quantities are scaled against each recipe's own serving count.
- The new **My Week** tab keeps the currently selected/generated weekly recipes in one easy-to-open place, including scaled ingredients, instructions, and source links where available.
- Changing servings refreshes the grocery list and My Week ingredient quantities immediately.
- Existing device data is preserved where possible. Built-in recipes are added automatically; saved edits and user-added recipes remain.

## Publish to GitHub Pages
1. Unzip this package.
2. Replace the corresponding files in your existing BradApp repository with these files.
3. Commit and push the changes to the branch/folder used by GitHub Pages.
4. Open the published site in Safari on your iPhone and refresh it. If the old version remains, close Safari, reopen the site, and refresh again; the service-worker cache has been bumped to force an update.
5. To refresh the Home Screen icon, remove the existing BradApp shortcut from the Home Screen and add it again from Safari's Share menu → Add to Home Screen.

This is an installable web app, not a native App Store build. User data is stored in that browser/device unless backed up.
