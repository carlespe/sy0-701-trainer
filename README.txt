SY0-701 Trainer - phone / web version
=====================================

This folder is a complete, self-contained web app. Put it online once,
then install it to your iPhone home screen and it works offline.

STEP 1 - PUT IT ONLINE (pick one)

  Netlify Drop (fastest, no command line)
    1. Go to  app.netlify.com/drop
    2. Drag this whole folder (or the .zip) onto the page.
    3. You get a URL like  random-name-123.netlify.app
       Copy it. That's your app address.

  GitHub Pages (if you already use GitHub)
    1. Make a new public repository.
    2. Upload every file in this folder to the root of it.
    3. Settings -> Pages -> Source: main branch, / (root). Save.
    4. Your URL is  yourname.github.io/reponame

  Either way the address must start with https:// - offline support
  will not switch on over plain http.

STEP 2 - INSTALL IT ON THE IPHONE

    1. Open that URL in SAFARI. Not Chrome - only Safari can install
       to the home screen on iOS.
    2. Tap the Share button (square with the up arrow).
    3. Scroll down and tap "Add to Home Screen".
    4. Name it and tap Add.

  It now has its own icon, opens full screen with no address bar,
  and keeps working with no signal.

STEP 3 - CHECK OFFLINE WORKS

  Open it once with signal so it can cache itself, then turn on
  Airplane Mode and open it again. It should load normally.

NOTES

  - Nothing is uploaded or tracked. All 270 questions, diagrams and
    answers are inside index.html.
  - Android: same steps, but in Chrome tap the menu and choose
    "Install app" or "Add to Home screen".
  - To update later, replace the files and change CACHE = 'sy0701-v1'
    in sw.js to 'sy0701-v2' so phones pick up the new version.

Developed by Espii
