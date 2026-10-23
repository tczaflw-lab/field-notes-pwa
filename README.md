# Field Notes

Field Notes is an installable listening player for iPhone and other devices. It keeps imported audio in the browser's local IndexedDB storage and adds a cached app shell so the interface can open offline after its first successful load.

## Open the app

GitHub Pages: https://tczaflw-lab.github.io/field-notes-pwa/

On iPhone, open that address in Safari, tap **Share** → **Add to Home Screen**, enable **Open as Web App**, then tap **Add**. Imported audio remains local to that browser/device and is not uploaded to this repository.

## Development

This is a static site. The player lives in index.html; PWA settings are in manifest.webmanifest and service-worker.js.
