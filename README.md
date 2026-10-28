# KyDrix Trading Challenge

A static website for tracking personal trading challenges. The app stores each visitor's data in that visitor's browser using local storage. It does not send or combine users' trading records.

## Publish with GitHub and Vercel

1. Create a new GitHub repository named `kydrix-trading-challenge`.
2. Upload `index.html`, `kydrix.css`, `kydrix.js`, `kydrix-logo.svg`, and `favicon.svg` from this folder to the repository's top level, then commit the files.
3. In Vercel, choose **Add New → Project**, connect GitHub if prompted, and import `kydrix-trading-challenge`.
4. Leave the project as a static site with no build command, then choose **Deploy**.
5. Share the `*.vercel.app` address. Future commits to the connected GitHub repository will redeploy the same Vercel project and keep its URL.

## Update the website

Replace the corresponding files in GitHub with the newer app files and commit the change. Vercel will publish the update to the existing project URL.

The Vercel Hobby plan is intended for personal, non-commercial use. Keep the app and its CDN-hosted Chart.js dependency online to use the charts.
