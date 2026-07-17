# BulkPix Studio

GitHub Pages-ready, fully client-side bulk image editor.

## Main features

- Upload individual photos or a complete folder
- Up to 1000 photos in one batch
- Default output: 400 x 400 px
- Default maximum size: 100 KB
- JPG, WebP and PNG output
- Fit, fill/crop and stretch modes
- Manual crop/zoom, pan, rotate and flip
- Brightness, contrast, saturation, grayscale, blur and sharpness
- Individual output size and KB override
- All processed photos download in one ZIP
- Android file-manager fallback when MIME type is blank
- Single-file build: all CSS and JavaScript are embedded in `index.html`

## GitHub Pages deployment

1. Extract the ZIP.
2. Create a public GitHub repository.
3. Upload `index.html`, `.nojekyll` and this `README.md` to the repository root.
4. Open **Settings > Pages**.
5. Select **Deploy from a branch**.
6. Select `main` and `/(root)`, then save.

Do not upload the outer ZIP as the website. Upload the files found inside it.

## Photo links

GitHub Pages cannot permanently store user-uploaded photos. Permanent public photo URLs need external storage such as Firebase Storage or Cloudinary. Once storage is configured, the app can provide a Copy Link button for every processed photo and export all URLs as CSV/TXT.

## Privacy

Image resizing, editing, compression and ZIP generation happen inside the browser. Photos are not sent to a server unless a separate cloud-storage integration is intentionally configured.
