# BradApp

A free, mobile-friendly recipe book and weekly meal planner designed for iPhone.

## Features
- Store and edit recipes in this browser on this device
- Generate or shuffle breakfast, lunch and dinner selections
- Create a combined ingredient list and check items off
- Share the menu and grocery list using your device's share options
- Import a recipe photo/screenshot and try browser OCR
- Export and restore a JSON backup

## Publish with GitHub Pages
1. Upload `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, and `icon-512.png` to the root of your repository.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then save.
5. Wait for the published URL to appear. Open it in Safari on your iPhone.
6. Tap **Share → Add to Home Screen**.

## Important notes
- Recipes are saved to local browser storage on the device and browser where they were entered. Export backups regularly.
- The app does not currently sync data between family members.
- OCR loads Tesseract.js from a public CDN and may require internet access. Always review extracted text.
- Grocery lines with similar but differently worded ingredients may need manual consolidation. Ingredient quantity arithmetic is intentionally not guessed across unlike units.
