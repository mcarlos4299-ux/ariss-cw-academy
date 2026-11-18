# ARISS CW Academy — PWA

Static installable web app adapted from the existing Google Apps Script Index.html.

## Publish on GitHub Pages
1. Upload all files and the `icons` folder to the repository root.
2. Go to Settings → Pages → Build and deployment, choose **Deploy from a branch**, **main**, **/(root)**, then Save.
3. Wait for the published URL to appear. Test all four training modes and audio.
4. On iPhone, open the site in Safari → Share → Add to Home Screen.

Offline access becomes available after the site loads successfully online and caches its assets.

The original Apps Script deployment remains unchanged.


## Version 2.1
On narrow screens the activity appears first, progress second, and Mission Guide becomes an expandable Help / Instructions section. The Morse key now reads “Press & Hold to Send Morse” and its check button reads “Check My Morse.” Desktop layout is unchanged. Service-worker cache version bumped to refresh installed PWA.
