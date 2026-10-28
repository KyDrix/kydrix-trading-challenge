# KyDrix Trading Challenge

A static website for tracking personal trading challenges. Each visitor's data stays in that visitor's own browser.

## Publish with GitHub and Vercel

1. Create a GitHub repository named `kydrix-trading-challenge`.
2. Upload `index.html`, `kydrix.css`, `kydrix.js`, `kydrix-logo.svg`, and `favicon.svg` to the repository's top level, then commit the files.
3. In Vercel, choose **Add New → Project**, connect GitHub if prompted, and import `kydrix-trading-challenge`.
4. Leave the project as a static site with no build command, then choose **Deploy**.
5. Share the `*.vercel.app` address. Future commits to GitHub redeploy to the same Vercel project URL.

The timezone selector is on the Account Metrics page in the monthly P/L calendar. It supports device time, UTC, and other IANA time zones. New CSV imports convert timestamps that include an offset or UTC/GMT header. Previously saved calendar dates are kept as recorded.

To update the website, replace the matching files in GitHub and commit the changes. The Vercel Hobby plan is intended for personal, non-commercial use.
