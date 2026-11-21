# Consent-based Location Share

A simple, static mobile-friendly location sharing page in Sinhala.

## How it works

1. A visitor checks the explicit consent box.
2. The visitor clicks **මගේ Location එක බලන්න** and their browser asks for location permission.
3. If permission is granted, the coordinates are displayed **only on their device**.
4. The visitor can choose to open WhatsApp and manually send the map link, or copy the link.

It does **not** secretly collect, store, forward, or report GPS data, IP addresses, account details, or browser fingerprints. No backend, database, or analytics are present. It cannot identify an unknown phone number owner.

## Publish on GitHub Pages

1. Create a new public GitHub repository (e.g. `location-share`).
2. Upload `index.html` and `.nojekyll` at the repository root; commit the files to `main`.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, then `main` and `/(root)`, and save.
5. Open the URL GitHub Pages provides. Browser location requires HTTPS, which GitHub Pages supports.

Note: accuracy depends on the visitor's device, environment, and permission. Location is never guaranteed exact.
