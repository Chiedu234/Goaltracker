GOALTRACKER 2026 — INSTALL ON YOUR IPHONE (free, ~5 minutes)

WHAT'S IN THIS FOLDER
  index.html            the app
  manifest.webmanifest  app metadata (name, icon, full-screen mode)
  sw.js                 makes it work offline
  icon-*.png            app icons

STEP 1 — PUT IT ONLINE (pick one, both free)

  Option A: GitHub Pages (permanent, recommended)
    1. Create a free account at github.com
    2. Click "+" -> New repository -> name it "goaltracker" -> Create
    3. Click "uploading an existing file" -> drag ALL files from this
       folder in -> Commit changes
    4. Repo Settings -> Pages -> Source: "Deploy from a branch" ->
       Branch: main, folder: / (root) -> Save
    5. Wait ~1 minute. Your app is live at:
       https://YOUR-USERNAME.github.io/goaltracker/

  Option B: Netlify
    1. Free account at netlify.com -> "Deploy manually"
    2. Drag this whole folder onto the drop zone -> done, you get a URL

STEP 2 — ADD TO YOUR HOME SCREEN
    1. Open that URL in SAFARI on your iPhone (must be Safari)
    2. Tap the Share button (square with arrow)
    3. Tap "Add to Home Screen" -> Add

That's it. It launches full-screen like a native app, works offline,
and your data is saved on your phone.

NOTES
  - Your data lives on your device (it never leaves your phone).
  - Use Stats -> Backup to export a JSON file occasionally, especially
    before switching phones or clearing Safari website data.
  - The app comes pre-loaded with your goals, habits, and sleep logs
    from your Excel tracker.
