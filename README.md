# Gym Tracker

A mobile-friendly gym app (pink theme for women, blue theme for men, chosen at setup): BMI and goal weight, weekly workout plan with YouTube how-to links,
daily meal plan, water tracker and weight progress chart. All data is saved on the user's own phone.

## Upload to GitHub and get a free link (GitHub Pages)

1. Sign in at https://github.com and click **New repository**. Name it `gym-tracker`, keep it **Public**, click **Create repository**.
2. Click **uploading an existing file**. Unzip this package first, then drag in everything inside the folder:
   `index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll`, `README.md` and the whole `icons` folder.
   (Upload the files themselves, not the zip.) Click **Commit changes**.
3. Open **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**,
   select branch **main** and folder **/ (root)**, then **Save**.
4. After 1 to 2 minutes your app is live at `https://YOUR-USERNAME.github.io/gym-tracker/`.

## Install on the phone

- **Android (Chrome):** open the link, tap the menu (three dots), then **Install app** or **Add to Home screen**.
- **iPhone (Safari):** open the link, tap **Share**, then **Add to Home Screen**.

The app then opens full screen with its own icon and works offline after the first visit.

## Notes

- Tap the round photo at the top of the app to add or change the profile picture. The photo stays on the phone.
- Use the same link every time. Data is stored per address, so a new address starts empty.
- Use Progress > Backup and restore to save progress or move to a new phone.
- To publish a change later, upload a new `index.html` and raise the number in `sw.js`
  (for example `gym-tracker-v2` to `gym-tracker-v3`) so phones pick up the update.

## Files

- `index.html` the whole app
- `manifest.webmanifest` name, colors and icons for installing
- `sw.js` offline support
- `icons/` app icons (192 and 512 px, maskable, Apple touch icon, favicons)
