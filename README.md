# Whose Interests — installable web app

Who funds each member of Congress, how they vote, and 20 key votes on veterans, the federal workforce, civil rights, and the budget. Every figure links to the original record.

Data snapshot: October 10, 2026 (FEC 2025–26 filings; roll calls through September 30, 2026).

## Put it online with GitHub Pages (free, about 5 minutes)

1. Create a free account at github.com if you don't have one.
2. Click **New repository**. Name it `whose-interests`, set it to **Public**, and click **Create repository**.
3. On the new repository page, click **uploading an existing file**. Drag in everything from this folder: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md`, and the five image files. Click **Commit changes**.
4. Go to **Settings → Pages**. Under **Branch**, choose `main` and `/ (root)`, then **Save**.
5. After a minute or two, the address appears at the top of that page, like `https://hochmoris-dev.github.io/self-or-public-interest/`.

The app must be served over https from a real web address to be installable. Opening `index.html` straight from your computer works as a page but cannot be installed.

## Install it

- **Android (Chrome):** open the address, then tap **Install app** on the page, or the menu (⋮) → **Install app** / **Add to Home screen**.
- **Windows (Edge):** open the address, then click **Install app** on the page, or the app icon in the address bar, or menu (…) → **Apps → Install this site as an app**. It then appears in the Start menu.
- **Windows (Chrome):** menu (⋮) → **Cast, save, and share → Install page as app**.
- **iPhone (Safari):** Share → **Add to Home Screen**.

After the first visit it works offline.

## Updating the data

Replace `index.html` with a new build, and change `VERSION` in `sw.js` (for example to `wi-2026-11-15`). Installed copies update the next time they open online.
