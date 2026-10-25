TZ phot edit - Android app (WebView shell around the TZ Photo Edit editor)

BUILD A - Android Studio: open this folder, wait for Gradle sync,
  Build > Build APK(s). Output: app/build/outputs/apk/debug/app-debug.apk

BUILD B - GitHub (no PC): new repo, upload this folder's contents,
  Actions > Build APK > Run workflow, download "TZ-phot-edit-apk".

EDITOR: app/src/main/assets/index.html (single file, no ads, no network).
editor-source/ holds the Studio modules (text, stickers, effects, backdrop, projects).

FEATURES ADDED: Text Studio (fonts, import your own fonts, stroke, shadow, glow,
gradient, curve, background box, quotes, re-edit), Stickers (emoji + 40 vector),
Effects (15 filters, adjust, vignette, grain, blur, pixelate, sharpen),
Backdrop (solid, gradient, 9 textures), Projects (autosave, rename, delete, reopen).
