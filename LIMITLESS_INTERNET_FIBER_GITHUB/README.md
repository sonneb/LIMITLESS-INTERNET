# LIMITLESS INTERNET FIBER

This is the current static HTML website project, prepared for GitHub Pages.

## Files
- `index.html` — website homepage.

## Publish with GitHub Pages
1. Create a new repository on GitHub (for example `limitless-internet-fiber`).
2. Upload `index.html` and this `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site; GitHub will show the website URL in Settings → Pages.

## Important current limitation
This is the existing browser-storage version of the website. Bookings, package settings and connection fees are stored in the visitor's browser using `localStorage`; they are not shared between different devices. Firebase Authentication and Cloud Firestore have **not** yet been connected. Do not use the demo administrator credentials (`admin` / `admin123`) for a public production website.

## Firebase connection still required
To enable shared bookings and secure customer/admin accounts, add the Firebase web app configuration and implement Firestore Authentication and Security Rules before using the site as a live multi-device customer portal. Never put a Firebase service-account private key in this website.
