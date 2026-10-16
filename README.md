# GenFren interactive site (Vercel-ready)

## Files
- `index.html` — standalone static website; no build step required.
- `assets/genlayer-logo.png` — the supplied official GenLayer logo.
- `assets/genlayer-mascot.png` — add the official mascot image (PNG or WebP is ideal).

The supplied GenLayer logo and a crop of the front-facing mascot from the supplied reference sheet are included.

## Deploy via GitHub + Vercel
1. The supplied logo is already included at `assets/genlayer-logo.png`.
2. The supplied front-facing mascot crop is already included at `assets/genlayer-mascot.png`.
3. Create a GitHub repository and upload `index.html` and the `assets` folder.
4. In Vercel, choose **Add New → Project**, import the GitHub repository.
5. For Framework Preset choose **Other**. Leave Build Command blank. Set Output Directory to `.` if Vercel asks for one.
6. Click **Deploy**.
7. Open the generated URL and test the answer buttons, scroll button, copy button, logo and mascot.
8. To make changes, edit the files in GitHub and commit. Vercel will redeploy automatically.
9. Share the production URL on X or LinkedIn.

## Notes
- This is a static HTML/CSS/JavaScript site, so no `npm install` or build command is needed.
- The interactive scenario is illustrative, not a complete representation of GenLayer's technical protocol.
- For social previews, consider adding a 1200×630 `assets/social-preview.png` and an `og:image` absolute URL once your site has a public domain.
