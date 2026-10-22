# SOLO SYSTEM Beta 3.2.5 — GitHub package (blank assistant assets)

## Package contents
- `index.html` — SOLO SYSTEM with Assistant Studio and no embedded default rank artwork.
- `assets/` — intentionally empty for now; rank-specific assistant PNGs will be created later.
- `manifest.webmanifest`, `app-icon.svg`, `app-icon-192.png`, `app-icon-512.png` — preserved PWA/install metadata and application icons. These are app icons, not rank assistant artwork.

## Assistant Studio
Assistant Studio supports separate PNG images for F, E, D, C, B, A, S, S+, and S++ ranks. Until you upload images, the assistant artwork area remains blank. Uploaded images are saved locally in this browser using IndexedDB; they are not automatically uploaded to GitHub. Use the Studio backup export/import to transfer customizations between browsers/devices.

## Publish with GitHub Pages
1. Extract this ZIP.
2. Upload the **contents** of the extracted folder to the repository root (including the `assets` folder).
3. In GitHub, open **Settings → Pages** and select **Deploy from a branch**, branch `main`, folder `/(root)`, then save.
4. Wait for the deployment and open the HTTPS site.

## Data and privacy
The hosted website uses browser storage for tracker data and custom assistant images. A local HTML file and the GitHub Pages site use different origins, so data does not automatically transfer. Export your tracker JSON backup from the old app and import it into the new one if needed. Keep personal JSON backups out of public repositories. GitHub Pages source files in a public repository are public.

## Notes
- Assistant PNG payloads have been removed from the HTML to keep this bundle lightweight. No default rank assistant artwork is included.
- The application icon files remain intentionally included so the PWA manifest stays functional.
