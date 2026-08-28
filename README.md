# BACKGROUND REMOVER

A minimal, client-side batch background removal web application.

## FEATURES

- Pure front-end processing using WebAssembly (`@imgly/background-removal`).
- Zero server involvement; images never leave the client device.
- Batch image uploading and simultaneous processing.
- Direct single or bulk PNG downloads (no `.zip` compression).
- Strict minimalist interface with zero rounded corners and zero icons.

## USAGE

1. Open `index.html` directly in any modern web browser, or host via GitHub Pages.
2. Drag and drop multiple images into the selection area.
3. Wait for WebAssembly execution.
4. Click **DOWNLOAD** on individual cards or **DOWNLOAD ALL** for sequential browser file exports.

## DEPLOYMENT

1. Push `index.html` to your GitHub repository root.
2. Navigate to **Settings > Pages**.
3. Select `main` branch and `/ (root)` folder, then save.

## LICENSE

MIT
