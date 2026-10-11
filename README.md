# InstaShopz

Instagram-style storefront app. Runs entirely in the browser — works on iPhone (Safari) and Windows (Edge/Chrome), installable, offline.

## Put it on GitHub Pages
1. Create a new repo on github.com (e.g. `instashopz`), set it to Public.
2. Click **Add file → Upload files** and drag in everything from this folder
   (`index.html`, `manifest.json`, `sw.js`, `README.md`, and the `icons` folder).
3. Commit. Then go to **Settings → Pages**, Source: **Deploy from a branch**, Branch: **main** / **(root)** → Save.
4. After ~1 minute your app is live at `https://<your-username>.github.io/instashopz/`.

## Install
- **iPhone:** open the link in Safari → Share → **Add to Home Screen**.
- **Windows:** open in Edge or Chrome → click the **Install app** icon in the address bar.

## Saving your store
Settings → Storage → **Save** writes a `.json` file with everything (items, photos, tags, collections, colors).
- Windows: first save picks the file; later saves overwrite it automatically. (Ctrl+S works too.)
- iPhone: Save → **Save to Files** → choose **Replace**.
Use **Import store** to load a `.json` someone sent you.
