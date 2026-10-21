# AfriAlphaApex Forex Intelligence Engine

**The Gold Master** — featuring **AfriPrime Copy Trader**.

GitHub / Netlify export of the current dashboard, 21 October 2026.

## Upload to GitHub

1. Extract this ZIP on your computer.
2. Create a GitHub repository (for example `afrialphaapex`).
3. Choose **Add file → Upload files**.
4. Upload the extracted `public` folder, `netlify.toml`, and `README.md` to the repository root. Include `.gitignore` if visible.
5. Commit the files. Do not upload only the ZIP, and do not nest everything inside another folder.

At the repository root you should see `netlify.toml` and `public/`. Inside `public/` is `index.html`.

## Deploy on Netlify

Import the GitHub repository into Netlify and select its main branch.

- Base directory: leave blank
- Build command: leave blank (no build step)
- Publish directory: `public`
- Environment variables: none required

The included `netlify.toml` sets the publish directory automatically.

For a manual Netlify upload, upload the `public` folder as the site content. Repository-based deployment is preferred so subsequent GitHub changes can be deployed automatically.

Official configuration reference: https://docs.netlify.com/build/configure-builds/file-based-configuration/

## Included

- Bright ivory/gold dashboard and gold balance emblem.
- TradingView chart widget with drawing toolbar enabled.
- Setup confirmation illustration, setup quality and lifecycle demos.
- TP1/TP2/TP3/SL milestone simulations and browser-local archive.
- Closed sample trades disappear from the recent view after 24 hours; archive retains them in this browser.
- AfriPrime Copy Trader feature, Exness registration link and sample copying preferences.
- Operations preview with no connected members or real commission data.

## Current status

This is a frontend prototype. It does not connect to MT5, place trades, verify referrals, authenticate members or host the Python copy core. The dashboard operations screen is a preview, not a protected admin area. No passwords or API keys are required.

The owner-only access of the original hosted preview is NOT carried into this static export. Configure Netlify access protection separately if you want a private preview. A private GitHub repository alone does not make the deployed website private.

Demo records and preferences are stored per browser and website origin. They will not transfer automatically from the previous hosted URL. TradingView requires internet access, shows an external provider rather than your Exness feed, and may be unavailable under browser/network restrictions; the Open TradingView link is retained.

The backend remains a separate Windows/server integration project. Do not upload broker credentials or `.env` files to GitHub or the `public` folder.

## Verification

Exported from source commit `0a38292dfd8dce4b246fad8909896ba3f8ad4336`. HTML copied unchanged; inline JavaScript syntax checked and Netlify configuration parsed. No deployment to your Netlify account has been performed.
