# Countdown page

A responsive, single-file countdown website with a photo gallery.

## Personalise
- Open `index.html` in a browser to preview.
- The default target date is **26 November 2027** (398 days after 24 October 2026). Change `targetDate` near the bottom of `index.html` if needed.
- The “Personalise this page” button changes the headline, target date and subtitle for the current preview.
- Photo picker lets you preview photos locally. For a published page, add your photos as image files in the repo and update the HTML to reference them (see publishing notes below). Photos chosen from the picker are not saved to the hosted site.

## Publish with GitHub Pages
1. Sign in to GitHub and create a new **public** repository, e.g. `countdown-page`.
2. Upload `index.html` and your selected photos (optional) to the repository root.
3. If you want permanent photos, edit the page to use image files committed to the repository; browser-selected photos are only local previews.
4. Open repository **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
6. Wait for the published URL shown in Settings → Pages.

## Alternatives
- **Netlify Drop**: easiest drag-and-drop publishing for a static page.
- **Cloudflare Pages**: good free static hosting, a little more setup.
- **Carrd**: easiest visual no-code builder, but a true live countdown and custom photo layout may require its paid features or embeds.

Privacy note: anyone with the public URL can see a public page and any photos uploaded with it. Avoid sensitive or private photos if the page is public.
