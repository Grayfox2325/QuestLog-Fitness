# QuestLog Fitness — Weight-Loss Campaign Build 4.0

QuestLog is a private, offline-first habit tracker that uses short video-game-style campaigns to support practical weight-loss behaviours without calorie logging, streak penalties, or complex workout programming.

## Build 4.0

- Daily Quest Board with a timed walk, healthy meal, no-impulse-delivery day, and weekly strength boss.
- Automatic walk rewards: 10 XP and coins for the first full five-minute block each day, then 5 for every additional block.
- Weekly weigh-ins with starting weight, current weight, total change, goal progress, a four-entry trend chart, and a clearly labelled estimated trajectory.
- Behaviour-based weigh-in rewards. XP is awarded for recording data, never for a particular scale result.
- Adaptive walking and strength targets. Promotion requires at least 80% completion for two consecutive weeks and must be accepted manually.
- User-created coin rewards with purchase history and Undo.
- Four-week campaigns covering walks, healthy meals, delivery choices, strength sessions, and weigh-ins.
- Weekly recaps, personal records, campaign trophies, cosmetic titles, and a penalty-free Resume Campaign flow.

## Deliberately excluded

QuestLog does not include calorie or macro tracking, GPS routes, step counting, social leaderboards, daily weigh-ins, barcode scanning, AI coaching, medication interpretation, or missed-day penalties.

## Data and upgrades

Progress is stored only in the browser under the existing `questlog-fitness-v1` storage key. Build 4 migrates Build 2 and Build 3 progress automatically, including XP, coins, walking history, trophies, and an active walk timer.

Use **Export backup** inside the app before clearing browser data or changing devices. The offline cache upgrades automatically to `questlog-fitness-v4`.

## Deploy

Upload all repository files to the site root or enable GitHub Pages from the `main` branch. Open the deployed site and confirm that the footer says **Build 4.0**.
