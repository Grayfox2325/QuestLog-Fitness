# QuestLog Fitness — Fixed Build 2.0

## What was broken

The deployed page referenced `app.js`, but that file was not uploaded to the GitHub repository. The manifest and service worker were also missing. The page therefore displayed correctly, but no JavaScript loaded and the buttons had no event handlers.

## Fix

This build puts all interface CSS and application JavaScript directly inside `index.html`, removing the missing-file failure point.

## Upload instructions

1. Open the root of the `QuestLog-Fitness` GitHub repository.
2. Choose **Add file → Upload files**.
3. Upload every file inside this folder directly into the repository root.
4. When GitHub reports conflicts, replace the existing files.
5. Commit the upload to the `main` branch.
6. Wait for the GitHub Pages deployment to finish.
7. Open the site in Chrome and verify that the footer says **Build 2.0**.
8. If the installed shortcut still shows the old build, close it completely and reopen it. If necessary, clear the site's cache or remove and reinstall the shortcut.

Progress continues to use the same `questlog-fitness-v1` browser storage key, so existing progress is retained.
