# TA Bill Creator (Android-friendly web app)

This is a starter app for preparing a Central Government TA bill on a phone. It is not an official government application and does not automatically validate entitlements or current TA/DA rates.

## Quick test on your phone
1. Extract this ZIP.
2. Open `index.html` in a browser if your phone's file manager allows it. Some browsers restrict local-file features.
3. For the best experience, publish the files with GitHub Pages and open the site in Chrome.
4. In Chrome, tap **⋮ > Add to Home screen** (or **Install app**, if shown).

## Publish using GitHub Pages
1. In your existing GitHub repository, open **Add file > Upload files**.
2. Upload `index.html`, `manifest.json`, and `sw.js` from this folder (upload the files themselves, not the ZIP).
3. Commit the changes.
4. Open repository **Settings > Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish; open the URL shown on the Pages screen on your Android phone.
7. In Chrome, choose **⋮ > Add to Home screen**.

## Included features
- Employee and journey details
- Manually entered travel fare, daily allowance, local conveyance, lodging, other charges
- Receipt-wise expense rows
- Total calculation and advance/deduction subtraction
- Save/load draft in this browser on this device
- Print or Save as PDF through the browser print dialog

## Important
- Enter amounts according to the applicable Central Government orders and your department's rules.
- Do not double-count an expense in both allowance fields and receipt items.
- Drafts are stored locally in the browser and are not backed up automatically.
- This prototype does not include login, cloud sync, official form formats, or automated rule-based entitlement calculations.
