# QuestLog Fitness

A free, private fitness quest tracker built for low-friction consistency.

## Included quests

- Minimum Movement: one five-minute walk per day, target five per week
- Bonus Movement: repeatable five-minute walking blocks
- Weekly Boss: one short strength circuit per week
- Eight cumulative trophies
- XP, levels, coins, weekly progress, history, undo, and backup import/export
- No streak penalties
- No account, ads, analytics, subscription, or server

## Fastest way to run it on a computer

1. Extract the ZIP.
2. Open a terminal in the extracted folder.
3. Run:

   python -m http.server 8000

4. Open `http://localhost:8000`.

Opening `index.html` directly also works for tracking, but installation and offline caching require the files to be served through HTTP/HTTPS.

## Install it on Android

The app must be hosted over HTTPS for Chrome to offer normal PWA installation.

Free deployment options:

### GitHub Pages

1. Create a new GitHub repository.
2. Upload every file from this folder to the repository root.
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Open the Pages address in Chrome on Android.
7. Tap the app's **Install** button or Chrome's menu → **Add to Home screen / Install app**.

### Netlify Drop

1. Extract the ZIP.
2. Open Netlify Drop in a desktop browser.
3. Drag the entire extracted folder onto the page.
4. Open the generated HTTPS address on Android.
5. Use Chrome's menu → **Add to Home screen / Install app**.

## Data

Progress is stored in browser local storage on the device. Use **Export backup** periodically. Clearing site data deletes local progress unless it has been exported.
