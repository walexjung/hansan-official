# HANSAN: WAR DIARY — Official website

Static bilingual landing page for the independent game **한산: 난중일기**. No build tools required.

## Publish on GitHub Pages

1. Sign in to GitHub using the account `walexjung` (verify account ownership).
2. Create a **public** repository called `hansan-official` (do not overwrite the existing `hansan-demo` repository).
3. Upload the contents of this folder to the root of the new repository: `index.html`, `README.md`, `images/`, and `.nojekyll`.
4. Go to **Settings → Pages → Build and deployment**.
5. Set **Source** to `Deploy from a branch`, and **Branch** to `main` and `/(root)`, then Save.
6. Once deployment finishes, check `https://walexjung.github.io/hansan-official/`.

## Before sharing widely

- Replace screenshot placeholders by adding **your own** `images/screenshot-1.jpg` and `images/screenshot-2.jpg`. Avoid film stills or other unlicensed promotional material.
- Check that the demo link `https://walexjung.github.io/hansan-demo/` works.
- The feedback link currently points to `https://github.com/walexjung/hansan-demo/issues/new`. Confirm the repo exists and Issues is enabled; otherwise replace it with a real Google Form / itch.io feedback URL.
- Reconfirm the STOVE review status, game title and the extent of AI disclosure before publication.
- Update store links when the store listing is live.
- If you have your own MP4 opening trailer, upload a **compressed** video or link to a hosted trailer; no video is bundled here.

## Change text / buttons

Open `index.html` in a text editor. Visible bilingual elements use `data-ko` and `data-en`. When changing copy, update both. Button destinations are standard `href` attributes.

## Local test

Double-click `index.html` or serve the directory using `python -m http.server 8000`. The page is responsive and saves preferred language locally in the browser.
