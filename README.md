# Happy Deepavali

A responsive, self-contained greeting page with animated diyas and fireworks. The greeting appears immediately. No installation, external fonts, or build step is required. Reduced-motion preferences are respected.

## Publish

In this repository, open **Settings → Pages → Build and deployment**, and choose **GitHub Actions** as the source. Push to `main` (or run the **Deploy Deepavali greeting** workflow under Actions).

The public page will be at https://tuan-faris.github.io/deepavali/ once deployment succeeds. The github.com repository URL displays source code; share the github.io URL for the greeting.

For a local preview, open `index.html` in a browser.

## Private selfie greeting
Visitors can use the camera/file picker, preview a centre-cropped photo, remove or replace it, or continue without a photo. The selected image is resized to 640 x 640 in browser memory. No photo upload, analytics, localStorage, database, or server storage is used. Refreshing clears the photo. Save my greeting generates a 1080 x 1560 PNG on the device. Camera picker and download presentation depend on the mobile browser.
