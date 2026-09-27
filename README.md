# Heritage CCTV Rollout Tracker

Project tracker for the supply, installation, testing and commissioning of CCTV systems at 34 Ministry of Culture heritage sites (SmartLife, 2026).

## Features
- **Dashboard** – overall progress (weighted by cameras), sites completed / in progress / delayed / not started, cameras installed, earned value, invoicing, open issues, material delivery, installation timeline, progress by team and by stage.
- **Sites** – 11 stages per site (Survey → As-built), actual dates, engineer, acceptance certificate, invoicing, remarks; filters, search and CSV export.
- **Daily log** – one line per site per day; cameras installed roll up automatically.
- **Materials** – delivered vs. required quantities per site (from the BOQ).
- **Issues** – issues & risks log with priority, owner, due date and status.
- **Settings** – project start date (working week Sunday–Thursday), stage weights, data backup / import / reset.

## Data
This is a static site with no server. All updates are saved in the browser (`localStorage`) on the device where they are made.
Use **Settings → Export backup** to share the latest data and **Import backup** to load it on another device.

## Hosting
Served with GitHub Pages from the `main` branch (root). Open `index.html` locally or visit the Pages URL.
