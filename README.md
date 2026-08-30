# FIRE Dashboard — GitHub Pages setup from Android

## 1. Create a repository
1. Open github.com.
2. Go to **Your repositories** → **New**.
3. Name it `fire-dashboard`.
4. Set it to **Public**.
5. Tap **Create repository**.

## 2. Upload the files
Upload these files from this ZIP into the repository root:
- `index.html`
- `manifest.webmanifest`
- `sw.js`

On GitHub mobile web:
1. Open the repository.
2. Tap **Add file** → **Upload files**.
3. Select the three files.
4. Tap **Commit changes**.

## 3. Enable GitHub Pages
1. Repository → **Settings** → **Pages**.
2. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: `main`
   - Folder: `/ (root)`
3. Tap **Save**.

GitHub will then show the Pages URL.

## 4. Put it on your Android home screen
1. Open the Pages URL in Chrome.
2. Tap **⋮**.
3. Choose **Install app**, **Add to Home screen**, or **Install and create shortcut**.
4. Confirm.

The page is configured with a web-app manifest and offline cache after the first successful load.
