# GitHub Pages Setup

Your privacy policy site is ready to be hosted on GitHub Pages!

## Quick Setup Steps

1. **Commit and push your changes** (if you haven't already):
   ```bash
   git add index.html
   git commit -m "Convert to single-page privacy policy"
   git push origin main
   ```

2. **Enable GitHub Pages**:
   - Go to your repository on GitHub: https://github.com/Siunami/sticker-pack-privacy-policy
   - Click **Settings** (in the repository menu)
   - Scroll down to **Pages** (in the left sidebar)
   - Under **Source**, select:
     - Branch: `main`
     - Folder: `/ (root)`
   - Click **Save**

3. **Your site will be live at**:
   ```
   https://siunami.github.io/sticker-pack-privacy-policy/
   ```

## Notes

- The `.nojekyll` file tells GitHub Pages not to process your HTML with Jekyll (which is good for a simple static site)
- Changes pushed to the `main` branch will automatically update the site (may take a minute or two)
- You can set a custom domain in the Pages settings if you have one

