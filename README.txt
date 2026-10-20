SHOP MANAGER — SOURCE FILES

This folder contains a first working prototype of Shop Manager:
- Inventory with cost price, selling price, stock and low-stock threshold
- Sales recording with automatic stock deductions
- Daily, last-7-days, monthly and all-time reports
- Gross profit based on cost price saved when each sale is recorded
- Local device storage and JSON backup/restore
- PWA manifest and service worker for offline web use

IMPORTANT
This is source code, not an APK. It must be hosted over HTTPS and then packaged with a trusted Android/PWA packaging service or Android build environment before it becomes an APK. Test the app and keep backups. Browser local storage can be erased by clearing app/site data; export backups regularly.

To publish using GitHub Pages from a phone:
1. Create/sign in to GitHub in your browser.
2. Create a new public repository named shop-manager-app.
3. Upload index.html, manifest.json, sw.js, icon-192.png and icon-512.png to the repository root.
4. In repository Settings > Pages, publish from the main branch and root folder.
5. Wait for GitHub Pages to provide an HTTPS URL.
6. Open the URL in Chrome and test adding products, recording a sale, turning off internet and reopening the app.
7. For APK packaging, use PWABuilder (pwabuilder.com) with the published HTTPS URL and follow its Android package instructions. Review signing options carefully and keep any signing key safe.

If a packaging service's interface changes, follow its current instructions rather than entering credentials or signing keys on an unknown site.
