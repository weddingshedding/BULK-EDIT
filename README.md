# BulkPix Studio

A fully client-side bulk photo resizing, compression and manual editing website made for GitHub Pages.

## Default output

- 400 × 400 px
- Maximum 100 KB
- JPG
- Fit inside frame
- White background

## Features

- Upload multiple photos or a complete folder
- Up to 1000 photos in one batch
- Resize all images together
- Compress JPG/WebP toward a maximum KB target
- JPG, WebP and PNG output
- Fit, fill/crop and stretch modes
- White, custom color or transparent background
- Manual edit for each photo
- Rotate, flip, zoom/crop, move X/Y
- Brightness, contrast, saturation, grayscale, blur and sharpness
- Individual custom width, height and KB settings
- Sequential processing to reduce browser memory pressure
- ZIP download and individual downloads
- No server upload. Photos stay in the browser

## Run locally

You can open `index.html` directly, or use a local server:

```bash
python -m http.server 5500
```

Then open `http://localhost:5500`.

## Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `styles.css`, `app.js` and `README.md` to the repository root.
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`.
6. Save. GitHub will show your live website link.

## Important notes

- “100 KB” means maximum target size, not an exact byte guarantee.
- Highly detailed images may remain above 100 KB even at very low quality.
- PNG compression is lossless, so the target KB may not be reached.
- Large batches depend on the user's browser, RAM and device power.
- The ZIP creator is included in the project, so no external JavaScript library is required.
