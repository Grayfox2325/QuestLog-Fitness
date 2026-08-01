# QuestLog Fitness — Walk Timer Build 3.0

## What is new

- A persistent start/stop walk timer that survives screen locking, switching apps, and reopening QuestLog.
- Actual whole walking minutes are recorded when a timed walk is stopped.
- The first full five-minute block of the day earns 10 XP and 10 coins. Every additional full block earns 5 XP and 5 coins.
- Partial five-minute blocks add to walking minutes but do not earn another reward block.
- An active timer can be discarded without changing progress.
- Manual five-minute walk buttons remain available as a fallback.
- Undo removes all minutes, XP, coins, and walk credits from a timed session.

## Reward examples

| Timed walk | Reward |
| ---: | ---: |
| 4:59 | No XP or coins |
| 5:00 | 10 XP, 10 coins |
| 9:59 | 10 XP, 10 coins |
| 10:00 | 15 XP, 15 coins |
| 20:00 | 25 XP, 25 coins |

## Upload instructions

1. Open the root of the `QuestLog-Fitness` GitHub repository.
2. Choose **Add file → Upload files**.
3. Upload every file inside this folder directly into the repository root.
4. When GitHub reports conflicts, replace the existing files.
5. Commit the upload to the `main` branch.
6. Wait for the GitHub Pages deployment to finish.
7. Open the site in Chrome and verify that the footer says **Build 3.0**.
8. If the installed shortcut still shows the old build, close it completely and reopen it. If necessary, clear the site's cache or remove and reinstall the shortcut.

Progress continues to use the same `questlog-fitness-v1` browser storage key, so existing progress is retained. The offline cache is upgraded automatically to `questlog-fitness-v3`.
