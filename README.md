# Haneul

A small, editable Korean learning web app. It has Look up, Translate, and Questions screens with Korean listen buttons, and is designed for iPhone Safari as well as desktop browsers.

## Run it

Open `index.html` to preview the interface on a computer. Online lookups and general translations need an internet connection. Common entries and the rule explanations are built in.

## Use it on iPhone

The app can read Korean aloud through your device’s built-in speech voice when available. Open it in iPhone Safari and tap a speaker button to listen.

The iPhone home-screen app needs the files hosted at an HTTPS address. One free option is GitHub Pages:

1. Put the files in the root of a GitHub repository.
2. In that repository, open **Settings → Pages** and publish from the `main` branch and `/ (root)`.
3. Open the resulting HTTPS address in iPhone Safari.
4. Tap **Share → Add to Home Screen**, turn on **Open as Web App**, then tap **Add**.

GitHub Pages is an optional hosting choice; this project itself has no paid hosting or app-store requirement. The translation service is third-party and free to use within its public limits. Text used for an uncached lookup or translation is sent to MyMemory; the app does not ask for an API key or payment details.

## Files

- `index.html` — app interface and behavior
- `manifest.webmanifest` — installable web-app metadata
- `sw.js` — offline cache for the app shell
- `icon.png` and `icon.svg` — app icons
