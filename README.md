# LAHVØID cards

Static site for GitHub Pages. Scanning the QR code opens `index.html`:
the first card shows for 5 seconds, then the second card fades in with a personal
`LHV-####` code. The code is stored in the visitor's browser (localStorage + cookie),
so scanning again on the same phone shows the same code.

## Put it online
1. Create a new GitHub repository (public).
2. Upload everything in this folder (`index.html` and the `assets` folder) to the repository root.
3. Repository **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder `/ (root)`. Save.
4. After a minute your site is live at `https://<your-username>.github.io/<repository-name>/`.
5. Turn that address into a QR code (any QR generator) and print it.

To change the delay, edit `DELAY` in `index.html` (milliseconds).
