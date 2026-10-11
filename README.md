# Hisaab

A small expense tracker you install on your phone. It records spending by category against monthly budgets, works offline, and stores everything on the phone itself. Nothing is sent to a server.

## Put it online (GitHub Pages, about 5 minutes)

1. On github.com, tap **+ → New repository**. Name it `hisaab`, choose **Public**, and tap **Create repository**.
2. Tap **uploading an existing file** and add all the files from this folder: `index.html`, `sw.js`, `manifest.webmanifest`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` and this `README.md`. Tap **Commit changes**.
3. Open **Settings → Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**, then pick branch **main** and folder **/ (root)**. Tap **Save**.
4. Wait a minute or two. The app goes live at `https://YOUR-USERNAME.github.io/hisaab/`.

The repository holds only the app's code. Your expenses never go to GitHub.

## Install on iPhone

1. Open `https://YOUR-USERNAME.github.io/hisaab/` in **Safari**. It must be Safari, not Chrome.
2. Tap **Share**, then **Add to Home Screen**, then **Add**.
3. From now on, open Hisaab from its icon. Enter all your expenses through the icon: the home-screen app keeps its data separate from Safari tabs.

## Keep your data safe

- Your data lives only in the app on this phone. Deleting the home-screen icon deletes the data with it.
- Every few weeks, go to **Budgets → Backup & restore → Back up now** and save the file to Files or iCloud Drive. The app reminds you once you have entries and haven't backed up for 30 days.
- On a new phone, install the app, then use **Restore from backup**.

## Move entries over from the Claude version

1. In the Claude version, tap **Clear examples** if you haven't already. Then go to **Entries → Export CSV**.
2. In the installed app, go to **Entries → Import CSV** and choose that file.

## Updating the app

Replace `index.html` in the repository with the new version, and change `hisaab-v1` to `hisaab-v2` in `sw.js`. The phone picks up the update the next time you open the app (sometimes it takes two opens).
