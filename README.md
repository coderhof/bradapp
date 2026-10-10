# BradApp

A free, mobile-friendly private recipe book and weekly meal planner for iPhone, with a clean navy-blue and white interface.

## Features
- Store and edit recipes in this browser on this device
- Generate or shuffle breakfast, lunch and dinner selections
- Create a combined ingredient list and check items off
- Share the menu and grocery list using your device share options
- Import a recipe photo/screenshot and try browser OCR
- Add source website/video links to recipes, with built-in searches for related inspiration
- Export and restore a JSON backup

## Publish with GitHub Pages
1. Upload `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`, and `bradapp-recipes-190.json` to the root of your repository.
2. Open **Settings → Pages** and choose **Deploy from a branch**, branch `main`, folder `/(root)`.
3. Open the published site in Safari on your iPhone and tap **Share → Add to Home Screen**.
4. In BradApp, use **Recipe Book → Restore backup** and select `bradapp-recipes-190.json`. Export your existing data first if you need to keep it; restoring replaces local app data.

## Recipe library
The JSON file contains 40 breakfast, 75 lunch, and 75 dinner recipe drafts, including 30 slow-cooker dinners. Recipe drafts should be checked for quantities, doneness, and food-safety guidance before relying on them. Built-in inspiration buttons search YouTube and the web for related recipes; they are not verified direct citations to the exact recipe.

Recipe data and meal plans are stored in local browser storage and do not sync between devices. Export backups regularly. Recipe photo OCR loads Tesseract.js from a public CDN and requires internet access.
